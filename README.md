# pd ia
simples ela te ajuda
export default function IAChatPDStudio() {
  return (
    <div className="min-h-screen bg-black text-white flex items-center justify-center p-6">
      <div className="w-full max-w-2xl bg-zinc-900 rounded-3xl shadow-2xl p-8 border border-zinc-700">
        <h1 className="text-4xl font-bold mb-2 text-center">PD AI</h1>
        <p className="text-zinc-400 text-center mb-8">
          Sua própria inteligência artificial
        </p>

        <div className="space-y-4">
          <div className="bg-zinc-800 p-4 rounded-2xl">
            <p className="text-sm text-zinc-400 mb-1">Usuário</p>
            <p>Como ganhar dinheiro na internet?</p>
          </div>

          <div className="bg-green-600 p-4 rounded-2xl">
            <p className="text-sm text-green-100 mb-1">PD AI</p>
            <p>
              Você pode ganhar dinheiro criando vídeos, fazendo artes,
              vendendo produtos ou ajudando empresas com IA.
            </p>
          </div>
        </div>

        <div className="mt-8 flex gap-3">
          <input
            className="flex-1 bg-zinc-800 border border-zinc-700 rounded-2xl px-4 py-3 outline-none"
            placeholder="Digite sua pergunta..."
          />

          <button className="bg-green-500 hover:bg-green-400 transition px-6 py-3 rounded-2xl font-bold">
            Enviar
          </button>
        </div>

        <div className="mt-8 grid grid-cols-2 gap-4">
          <div className="bg-zinc-800 p-4 rounded-2xl">
            <h2 className="font-bold mb-2">Funções</h2>
            <ul className="text-sm text-zinc-400 space-y-1">
              <li>• Responde perguntas</li>
              <li>• Dá ideias</li>
              <li>• Ajuda nos estudos</li>
            </ul>
          </div>

          <div className="bg-zinc-800 p-4 rounded-2xl">
            <h2 className="font-bold mb-2">Futuro</h2>
            <ul className="text-sm text-zinc-400 space-y-1">
              <li>• Colocar voz</li>
              <li>• Criar app</li>
              <li>• Ganhar dinheiro com anúncios</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  );
}
