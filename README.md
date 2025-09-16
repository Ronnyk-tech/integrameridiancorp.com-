import React from "react";

// Single-file React component for a simple professional landing page
// Tailwind CSS classes are used (assumes Tailwind is available in the project)
// Default export is the page component. Replace placeholder values where needed.

export default function IntegraMeridianPage() {
  return (
    <div className="min-h-screen bg-gray-50 text-slate-800">
      <header className="bg-white shadow">
        <div className="max-w-5xl mx-auto px-6 py-6 flex items-center justify-between">
          <div className="flex items-center space-x-4">
            <div className="w-12 h-12 rounded-lg bg-gradient-to-br from-indigo-600 to-sky-500 flex items-center justify-center text-white font-bold">IM</div>
            <div>
              <h1 className="text-xl font-semibold">INTEGRA MERIDIAN CORP</h1>
              <p className="text-sm text-slate-500">Reliable shipping & logistics — API integration ready</p>
            </div>
          </div>
          <nav className="text-sm text-slate-600 space-x-4 hidden md:flex">
            <a href="#about" className="hover:underline">About</a>
            <a href="#services" className="hover:underline">Services</a>
            <a href="#technical" className="hover:underline">API / Tech</a>
            <a href="#contact" className="hover:underline">Contact</a>
          </nav>
        </div>
      </header>

      <main className="max-w-5xl mx-auto px-6 py-12">
        <section className="bg-white rounded-2xl shadow-md p-8 mb-8">
          <div className="grid md:grid-cols-2 gap-8 items-center">
            <div>
              <h2 className="text-3xl font-extrabold leading-tight">USPS API Integration • Labels • Returns</h2>
              <p className="mt-4 text-slate-600">INTEGRA MERIDIAN CORP is set up to integrate directly with shipping carriers via API. This page provides the company and developer contact details for carrier verification and any technical onboarding required.</p>

              <ul className="mt-6 space-y-3 text-sm text-slate-700">
                <li>• In-house / custom API integration (not using third-party vendors)</li>
                <li>• Shipping & returns label generation (domestic & international)</li>
                <li>• Testing & production workflows ready — developer contact available</li>
              </ul>

              <div className="mt-6 flex space-x-3">
                <a href="#contact" className="inline-flex items-center px-4 py-2 rounded-lg bg-indigo-600 text-white font-medium shadow">Contact Developer</a>
                <a href="#technical" className="inline-flex items-center px-4 py-2 rounded-lg border border-slate-200 text-slate-700">API / Technical</a>
              </div>
            </div>

            <div className="bg-slate-50 border border-slate-100 rounded-lg p-6">
              <h3 className="text-lg font-semibold">Company Snapshot</h3>
              <div className="mt-3 text-sm text-slate-700 space-y-2">
                <div><strong>Company:</strong> INTEGRA MERIDIAN CORP</div>
                <div><strong>Email:</strong> <a href="mailto:Obsheakovii@mail.ru" className="text-indigo-600 hover:underline">Obsheakovii@mail.ru</a></div>
                <div><strong>Phone:</strong> (407) 271-7973</div>
                <div><strong>Website:</strong> <em>Replace with your custom domain</em></div>
              </div>

              <p className="mt-4 text-xs text-slate-500">Tip: Add your CRID, MID, and Consumer Key in the technical section so USPS can verify account details quickly.</p>
            </div>
          </div>
        </section>

        <section id="about" className="mb-8">
          <div className="bg-white rounded-2xl shadow-md p-8">
            <h3 className="text-2xl font-bold">About INTEGRA MERIDIAN</h3>
            <p className="mt-4 text-slate-600">We provide shipping and logistics solutions with direct API integrations to major carriers. Our platform will be used to generate outbound and return shipping labels programmatically. We aim for secure, auditable, and production-ready label generation with clear developer contact for any integration support.</p>
          </div>
        </section>

        <section id="services" className="mb-8">
          <div className="bg-white rounded-2xl shadow-md p-8">
            <h3 className="text-2xl font-bold">Services</h3>
            <div className="mt-6 grid sm:grid-cols-2 gap-6">
              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Label Generation</h4>
                <p className="text-sm text-slate-600 mt-2">Programmatic creation of outbound and return labels (domestic & international).</p>
              </div>
              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Rate Calculation</h4>
                <p className="text-sm text-slate-600 mt-2">Real-time shipment rates and service selection for optimized shipping costs.</p>
              </div>
              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Tracking & Notifications</h4>
                <p className="text-sm text-slate-600 mt-2">Automated tracking updates and webhook support for shipment lifecycle events.</p>
              </div>
              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Returns Management</h4>
                <p className="text-sm text-slate-600 mt-2">Customer-friendly return labels and workflows to simplify reverse logistics.</p>
              </div>
            </div>
          </div>
        </section>

        <section id="technical" className="mb-8">
          <div className="bg-white rounded-2xl shadow-md p-8">
            <h3 className="text-2xl font-bold">API / Technical Details</h3>
            <p className="mt-3 text-slate-600">Use this section to provide USPS the technical credentials and integration notes for verification.</p>

            <div className="mt-6 grid md:grid-cols-2 gap-6">
              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Account IDs</h4>
                <div className="mt-3 text-sm text-slate-700 space-y-2">
                  <div><strong>CRID:</strong> <em>(add CRID here)</em></div>
                  <div><strong>Outbound MID:</strong> <em>(add MID)</em></div>
                  <div><strong>Returns MID:</strong> <em>(add MID)</em></div>
                  <div><strong>EPS Account:</strong> <em>(add EPS account number)</em></div>
                </div>
              </div>

              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Web Tools / API</h4>
                <div className="mt-3 text-sm text-slate-700 space-y-2">
                  <div><strong>Consumer Key:</strong> <em>(add Consumer Key)</em></div>
                  <div><strong>Integration Type:</strong> In-house / custom API (not vendor)</div>
                  <div><strong>Testing:</strong> Sandbox available — ready to share test endpoints</div>
                </div>
              </div>
            </div>

            <div className="mt-6 text-sm text-slate-600">If needed, include a short note about expected daily shipment volume so the Sales team can provision level-3 access appropriately.</div>
          </div>
        </section>

        <section id="contact" className="mb-8">
          <div className="bg-white rounded-2xl shadow-md p-8">
            <h3 className="text-2xl font-bold">Contact & Developer</h3>

            <div className="mt-6 grid md:grid-cols-2 gap-6 items-start">
              <div>
                <h4 className="font-semibold">Primary Contact</h4>
                <p className="mt-2 text-sm text-slate-700">INTEGRA MERIDIAN CORP<br />Email: <a href="mailto:Obsheakovii@mail.ru" className="text-indigo-600 hover:underline">Obsheakovii@mail.ru</a><br />Phone: (407) 271-7973</p>

                <h4 className="mt-4 font-semibold">Developer / Technical Contact</h4>
                <p className="mt-2 text-sm text-slate-700">Provide developer contact information here (email & phone). They will be the liaison for any technical onboarding calls or testing requests from USPS.</p>

                <div className="mt-6">
                  <a href="mailto:Obsheakovii@mail.ru" className="inline-block px-4 py-2 rounded-lg bg-indigo-600 text-white">Email Us</a>
                </div>
              </div>

              <div className="p-4 border border-slate-100 rounded-lg">
                <h4 className="font-semibold">Quick Links (for USPS)</h4>
                <ul className="mt-3 text-sm text-slate-700 space-y-2">
                  <li><strong>GitHub Project:</strong> <em>Replace with your repo URL</em></li>
                  <li><strong>Staging Site:</strong> <em>Replace with your staging URL (if any)</em></li>
                  <li><strong>Production Domain:</strong> <em>Replace with your purchased domain</em></li>
                </ul>
              </div>
            </div>

            <p className="mt-6 text-xs text-slate-500">Note: Do not share sensitive keys publicly. Provide Consumer Key and account IDs via secure email to USPS MRC or Sales as requested.</p>
          </div>
        </section>

        <footer className="mt-8 py-8 text-center text-sm text-slate-500">
          © {new Date().getFullYear()} INTEGRA MERIDIAN CORP — Built for USPS API onboarding
        </footer>
      </main>
    </div>
  );
}
