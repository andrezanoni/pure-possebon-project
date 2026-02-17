export default function PurePossebon() { return ( <div className="min-h-screen bg-neutral-50 text-neutral-900"> {/* Hero Section */} <section className="flex flex-col items-center justify-center text-center px-6 py-24 bg-gradient-to-b from-white to-neutral-100"> <h1 className="text-5xl md:text-6xl font-bold tracking-tight mb-6"> Pure Possebon </h1> <p className="text-lg md:text-xl max-w-2xl text-neutral-600 mb-8"> Beleza consciente, formulações inteligentes e identidade marcante. Uma marca criada para evoluir com você. </p> <button className="bg-black text-white px-8 py-3 rounded-2xl text-sm tracking-wide hover:opacity-90 transition"> Conheça a Coleção </button> </section>

{/* About Section */}
  <section className="px-6 py-20 max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
    <div>
      <h2 className="text-3xl font-semibold mb-6">Nossa Essência</h2>
      <p className="text-neutral-600 leading-relaxed">
        A Pure Possebon nasce da união entre ciência, estética e propósito.
        Desenvolvemos produtos com rigor técnico e sensibilidade artística,
        priorizando qualidade, segurança e experiência sensorial.
      </p>
    </div>
    <div className="bg-neutral-200 rounded-2xl h-80 shadow-inner" />
  </section>

  {/* Products Section */}
  <section className="bg-white px-6 py-20">
    <div className="max-w-6xl mx-auto">
      <h2 className="text-3xl font-semibold text-center mb-16">
        Nossos Produtos
      </h2>
      <div className="grid md:grid-cols-3 gap-8">
        <div className="bg-neutral-50 p-8 rounded-2xl shadow-sm hover:shadow-md transition">
          <h3 className="text-xl font-medium mb-4">Bálsamos Labiais</h3>
          <p className="text-neutral-600 text-sm">
            Hidratação profunda com acabamento elegante e textura equilibrada.
          </p>
        </div>

        <div className="bg-neutral-50 p-8 rounded-2xl shadow-sm hover:shadow-md transition">
          <h3 className="text-xl font-medium mb-4">Batons</h3>
          <p className="text-neutral-600 text-sm">
            Pigmentação sofisticada com conforto e fixação duradoura.
          </p>
        </div>

        <div className="bg-neutral-50 p-8 rounded-2xl shadow-sm hover:shadow-md transition">
          <h3 className="text-xl font-medium mb-4">Coleções Exclusivas</h3>
          <p className="text-neutral-600 text-sm">
            Linhas autorais desenvolvidas com conceito, identidade e inovação.
          </p>
        </div>
      </div>
    </div>
  </section>

  {/* Contact Section */}
  <section className="bg-neutral-900 text-white px-6 py-20">
    <div className="max-w-4xl mx-auto text-center">
      <h2 className="text-3xl font-semibold mb-8">Entre em Contato</h2>
      <p className="text-neutral-300 mb-4">
        Email: contatoEeFlinhalabial@gmail.com.br
      </p>
      <p className="text-neutral-300 mb-8">
        WhatsApp: (11) 94847-1779
      </p>
      <button className="bg-white text-black px-8 py-3 rounded-2xl text-sm tracking-wide hover:opacity-90 transition">
        Falar com a Pure Possebon
      </button>
    </div>
  </section>

  {/* Footer */}
  <footer className="bg-black text-neutral-400 text-sm text-center py-6">
    © {new Date().getFullYear()} Pure Possebon. Todos os direitos reservados.
  </footer>
</div>

); }
