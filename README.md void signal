export default function VoidSignalLanding() {
  return (
    <div className="min-h-screen bg-black text-white font-sans overflow-hidden">
      {/* Background */}
      <div className="fixed inset-0 opacity-20 pointer-events-none">
        <div className="absolute inset-0 bg-[radial-gradient(circle_at_center,rgba(255,255,255,0.08),transparent_60%)]" />
        <div className="absolute inset-0 bg-[linear-gradient(rgba(255,255,255,0.03)_1px,transparent_1px),linear-gradient(90deg,rgba(255,255,255,0.03)_1px,transparent_1px)] bg-[size:40px_40px]" />
      </div>

      {/* Navbar */}
      <header className="relative z-10 border-b border-white/10 backdrop-blur-sm">
        <div className="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
          <div>
            <h1 className="text-3xl font-black tracking-[0.3em]">VOID//SIGNAL</h1>
            <p className="text-xs text-white/40 tracking-[0.4em] mt-1">
              BORN FROM STATIC
            </p>
          </div>

          <nav className="hidden md:flex gap-10 text-sm tracking-widest text-white/70 uppercase">
            <a href="#" className="hover:text-white transition">Packs</a>
            <a href="#" className="hover:text-white transition">Identity</a>
            <a href="#" className="hover:text-white transition">Community</a>
            <a href="#" className="hover:text-white transition">Drops</a>
          </nav>

          <button className="border border-white/20 px-5 py-2 rounded-full hover:bg-white hover:text-black transition uppercase tracking-widest text-sm">
            Enter
          </button>
        </div>
      </header>

      {/* Hero */}
      <section className="relative z-10 max-w-7xl mx-auto px-6 pt-24 pb-20 grid lg:grid-cols-2 gap-14 items-center">
        <div>
          <p className="uppercase tracking-[0.5em] text-white/40 text-xs mb-6">
            Signal Detected
          </p>

          <h2 className="text-6xl md:text-8xl font-black leading-[0.9] tracking-tight">
            IDENTITY.
            <br />
            AESTHETIC.
            <br />
            PRESENCE.
          </h2>

          <p className="mt-8 text-white/60 text-lg max-w-xl leading-relaxed">
            Digital identity platform for creators, streamers and artists who
            refuse generic aesthetics.
          </p>

          <div className="flex flex-wrap gap-4 mt-10">
            <button className="bg-white text-black px-8 py-4 rounded-full font-bold tracking-widest uppercase hover:scale-105 transition">
              Explore Packs
            </button>

            <button className="border border-white/20 px-8 py-4 rounded-full tracking-widest uppercase hover:bg-white hover:text-black transition">
              Create Identity
            </button>
          </div>

          <div className="mt-14 grid grid-cols-3 gap-6">
            <div>
              <h3 className="text-4xl font-black">+50K</h3>
              <p className="text-white/40 uppercase text-xs tracking-[0.3em] mt-2">
                Downloads
              </p>
            </div>

            <div>
              <h3 className="text-4xl font-black">+500</h3>
              <p className="text-white/40 uppercase text-xs tracking-[0.3em] mt-2">
                Identities
              </p>
            </div>

            <div>
              <h3 className="text-4xl font-black">+200</h3>
              <p className="text-white/40 uppercase text-xs tracking-[0.3em] mt-2">
                Packs
              </p>
            </div>
          </div>
        </div>

        {/* Right visual */}
        <div className="relative flex items-center justify-center">
          <div className="absolute w-[500px] h-[500px] rounded-full border border-white/10 animate-pulse" />
          <div className="absolute w-[420px] h-[420px] rounded-full border border-white/5" />

          <div className="relative bg-white/5 border border-white/10 rounded-[2rem] p-8 backdrop-blur-xl shadow-2xl w-full max-w-lg">
            <div className="flex items-center justify-between border-b border-white/10 pb-4 mb-6">
              <span className="text-white/40 uppercase tracking-[0.3em] text-xs">
                VOID//SIGNAL CORE
              </span>

              <span className="text-green-400 text-xs tracking-widest uppercase">
                Online
              </span>
            </div>

            <div className="aspect-square rounded-[1.5rem] bg-gradient-to-b from-white/10 to-transparent border border-white/10 flex items-center justify-center overflow-hidden relative">
              <div className="absolute inset-0 bg-[radial-gradient(circle_at_center,rgba(255,255,255,0.2),transparent_70%)]" />

              <div className="text-center z-10">
                <div className="text-8xl font-black tracking-[0.2em]">
                  V//S
                </div>

                <p className="text-white/40 uppercase tracking-[0.4em] text-xs mt-4">
                  Transmission Active
                </p>
              </div>
            </div>

            <div className="grid grid-cols-3 gap-3 mt-6">
              {['NULL PACK', 'BLACK STATIC', 'SYSTEM CORE'].map((item) => (
                <div
                  key={item}
                  className="border border-white/10 rounded-xl p-3 text-center text-xs tracking-widest uppercase text-white/60 hover:bg-white hover:text-black transition cursor-pointer"
                >
                  {item}
                </div>
              ))}
            </div>
          </div>
        </div>
      </section>

      {/* Featured Packs */}
      <section className="relative z-10 max-w-7xl mx-auto px-6 py-20 border-t border-white/10">
        <div className="flex items-end justify-between mb-12">
          <div>
            <p className="text-white/40 uppercase tracking-[0.4em] text-xs mb-3">
              Featured Drops
            </p>

            <h3 className="text-5xl font-black">PACKS</h3>
          </div>

          <button className="uppercase tracking-[0.3em] text-sm text-white/60 hover:text-white transition">
            View All
          </button>
        </div>

        <div className="grid md:grid-cols-3 gap-8">
          {[
            {
              title: 'NULL PACK',
              desc: 'Overlays • Alerts • Banners',
              price: 'R$29,90',
            },
            {
              title: 'BLACK STATIC',
              desc: 'Transitions • Loops • UI',
              price: 'R$39,90',
            },
            {
              title: 'SYSTEM COLLAPSE',
              desc: 'Complete Identity System',
              price: 'R$49,90',
            },
          ].map((pack) => (
            <div
              key={pack.title}
              className="group border border-white/10 rounded-[2rem] overflow-hidden bg-white/[0.03] hover:bg-white/[0.06] transition"
            >
              <div className="h-72 bg-gradient-to-b from-white/10 to-transparent flex items-center justify-center text-5xl font-black tracking-[0.2em]">
                V//S
              </div>

              <div className="p-6">
                <h4 className="text-2xl font-black tracking-wide">
                  {pack.title}
                </h4>

                <p className="text-white/40 uppercase tracking-[0.2em] text-xs mt-3">
                  {pack.desc}
                </p>

                <div className="flex items-center justify-between mt-8">
                  <span className="text-xl font-bold">{pack.price}</span>

                  <button className="border border-white/10 px-5 py-2 rounded-full text-xs uppercase tracking-[0.3em] hover:bg-white hover:text-black transition">
                    Access
                  </button>
                </div>
              </div>
            </div>
          ))}
        </div>
      </section>

      {/* CTA */}
      <section className="relative z-10 max-w-7xl mx-auto px-6 py-24">
        <div className="border border-white/10 rounded-[3rem] p-12 md:p-20 bg-white/[0.03] backdrop-blur-xl text-center relative overflow-hidden">
          <div className="absolute inset-0 bg-[radial-gradient(circle_at_top,rgba(255,255,255,0.08),transparent_70%)]" />

          <div className="relative z-10">
            <p className="uppercase tracking-[0.5em] text-white/40 text-xs mb-6">
              Join The Transmission
            </p>

            <h3 className="text-5xl md:text-7xl font-black leading-none">
              NOT MADE
              <br />
              FOR EVERYONE.
            </h3>

            <p className="max-w-2xl mx-auto text-white/60 text-lg mt-8 leading-relaxed">
              Become part of a digital movement built for creators with
              identity, presence and vision.
            </p>

            <button className="mt-10 bg-white text-black px-10 py-4 rounded-full font-black uppercase tracking-[0.3em] hover:scale-105 transition">
              Enter Void//Signal
            </button>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="relative z-10 border-t border-white/10 py-10 px-6">
        <div className="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6 text-white/40 text-sm tracking-widest uppercase">
          <span>VOID//SIGNAL © 2026</span>
          <span>Built For Outsiders</span>
        </div>
      </footer>
    </div>
  )
}
