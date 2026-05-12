# koiloimport React from 'react';

export default function KoiloHome() {
  return (
    <div className="min-h-screen bg-slate-50 flex flex-col items-center justify-center p-6">
      <main className="max-w-2xl w-full bg-white shadow-xl rounded-3xl p-10 border border-slate-100">
        <div className="flex items-center space-x-4 mb-6">
          <div className="w-12 h-12 bg-indigo-600 rounded-xl flex items-center justify-center text-white font-bold text-2xl">
            K
          </div>
          <h1 className="text-4xl font-extrabold text-slate-900 tracking-tight">koilo</h1>
        </div>
        
        <p className="text-lg text-slate-600 mb-8 leading-relaxed">
          The core engine for your next decentralized indexing project. 
          Built for speed, simplicity, and scale.
        </p>

        <div className="grid grid-cols-1 gap-4">
          <div className="p-4 bg-slate-50 rounded-lg border border-slate-200">
            <code className="text-sm text-indigo-600 font-mono">npm install @koilo/core</code>
          </div>
          <button className="w-full py-4 bg-slate-900 text-white rounded-xl font-semibold hover:bg-slate-800 transition-colors shadow-lg">
            Initialize Project
          </button>
        </div>
      </main>

      <footer className="mt-12 text-slate-400 text-sm font-medium">
        © 2026 Koilo Systems • [creatorlife240](https://github.com/creatorlife240)
      </footer>
    </div>
  );
}
