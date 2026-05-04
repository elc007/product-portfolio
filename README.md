export default function ErickPortfolio() {
  return (
    <div className="min-h-screen bg-slate-950 text-white">
      <section className="max-w-5xl mx-auto px-6 py-16">

        {/* HEADER */}
        <div className="mb-12">
          <p className="text-sm tracking-[0.2em] text-slate-400 uppercase">
            Product Portfolio
          </p>
          <h1 className="text-5xl font-bold mt-3">Erick Costa</h1>
          <p className="text-xl text-slate-300 mt-4 max-w-3xl">
            Product Manager focused on SaaS, integrations, and building scalable solutions that reduce operational complexity and drive measurable impact.
          </p>
        </div>

        {/* IMPACT METRICS */}
        <div className="grid md:grid-cols-2 gap-6 mb-12">
          <div className="bg-slate-900 rounded-2xl p-6 border border-slate-800">
            <h2 className="text-4xl font-bold">50%</h2>
            <p className="text-slate-300 mt-2">
              Reduced bug resolution SLA, increasing product reliability and customer satisfaction.
            </p>
          </div>

          <div className="bg-slate-900 rounded-2xl p-6 border border-slate-800">
            <h2 className="text-4xl font-bold">70%</h2>
            <p className="text-slate-300 mt-2">
              Reduced cargo release time through automated customs clearance at a major airport.
            </p>
          </div>
        </div>

        {/* CASE STUDIES */}
        <div className="mb-12">
          <h2 className="text-3xl font-semibold mb-6">Case Studies</h2>

          <div className="grid md:grid-cols-2 gap-6">
            <div className="bg-slate-900 rounded-2xl p-6 border border-slate-800 hover:border-slate-600 transition">
              <h3 className="text-2xl font-semibold mb-3">SAP + SaaS Integration</h3>
              <p className="text-slate-300 mb-4">
                Led end-to-end integration between ERP and SaaS systems, improving data consistency across operations.
              </p>
              <ul className="text-sm text-slate-400 space-y-1">
                <li>• Complex system integration</li>
                <li>• Data reliability</li>
                <li>• Cross-functional coordination</li>
              </ul>
            </div>

            <div className="bg-slate-900 rounded-2xl p-6 border border-slate-800 hover:border-slate-600 transition">
              <h3 className="text-2xl font-semibold mb-3">OCR + AI Data Extraction</h3>
              <p className="text-slate-300 mb-4">
                Implemented OCR and AI workflows to extract data from unstructured documents and reduce manual effort.
              </p>
              <ul className="text-sm text-slate-400 space-y-1">
                <li>• AI-driven automation</li>
                <li>• Workflow optimization</li>
                <li>• Efficiency gains</li>
              </ul>
            </div>
          </div>
        </div>

        {/* PRODUCT THINKING */}
        <div className="bg-slate-900 rounded-2xl p-6 border border-slate-800 mb-12">
          <h2 className="text-2xl font-semibold mb-4">Product Thinking</h2>

          <div className="grid md:grid-cols-3 gap-4 text-slate-300">
            <div>
              <h3 className="font-medium text-white mb-2">Strategy</h3>
              <p>Connecting business goals with product execution and measurable outcomes.</p>
            </div>

            <div>
              <h3 className="font-medium text-white mb-2">Execution</h3>
              <p>Managing risks, dependencies, and delivering in complex environments.</p>
            </div>

            <div>
              <h3 className="font-medium text-white mb-2">Analytics</h3>
              <p>Using data and user behavior to guide product decisions.</p>
            </div>
          </div>
        </div>

        {/* CONTACT */}
        <div className="border-t border-slate-800 pt-8 text-slate-400 text-sm">
          <p>LinkedIn: linkedin.com/in/erick-lima-costa</p>
          <p>Email: elc007@gmail.com</p>
        </div>

      </section>
    </div>
  );
}
