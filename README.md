<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Tickets BR - Checkout</title>
</head>
<body class="bg-gray-50 font-sans">

    <div class="bg-red-600 text-white text-center py-2 text-sm font-bold animate-pulse">
        ⚠️ ATENÇÃO: Últimos ingressos para a categoria Cadeira Inferior!
    </div>

    <nav class="bg-white shadow-sm p-4 flex justify-between items-center">
        <div class="text-2xl font-bold text-blue-600">TICKETS<span class="text-yellow-500">BR</span></div>
        <div class="text-gray-500 text-sm">Ambiente 100% Seguro 🔒</div>
    </nav>

    <main class="max-w-4xl mx-auto p-6 grid grid-cols-1 md:grid-cols-2 gap-8">
        
        <div class="space-y-4">
            <h2 class="text-xl font-bold text-gray-800">Selecione seu Setor</h2>
            
            <label class="block border-2 border-blue-600 bg-blue-50 p-4 rounded-xl cursor-pointer hover:border-blue-700 transition">
                <div class="flex justify-between items-center">
                    <div>
                        <p class="font-bold text-gray-800">Cadeira Superior</p>
                        <p class="text-xs text-gray-500">Visão panorâmica do estádio</p>
                    </div>
                    <p class="font-bold text-blue-600 text-lg">R$ 1.250</p>
                </div>
            </label>

            <label class="block border border-gray-200 bg-white p-4 rounded-xl cursor-pointer hover:border-blue-500 transition relative">
                <span class="absolute -top-3 right-4 bg-yellow-400 text-[10px] font-bold px-2 py-1 rounded-full uppercase">Mais Vendido</span>
                <div class="flex justify-between items-center">
                    <div>
                        <p class="font-bold text-gray-800">Cadeira Inferior</p>
                        <p class="text-xs text-gray-500">Próximo ao gramado</p>
                    </div>
                    <p class="font-bold text-gray-700 text-lg">R$ 2.800</p>
                </div>
            </label>

            <label class="block border border-gray-200 bg-white p-4 rounded-xl cursor-pointer hover:border-blue-500 transition">
                <div class="flex justify-between items-center">
                    <div>
                        <p class="font-bold text-gray-800">Camarote VIP</p>
                        <p class="text-xs text-gray-500">Open bar e buffet incluso</p>
                    </div>
                    <p class="font-bold text-gray-700 text-lg">R$ 5.900</p>
                </div>
            </label>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-lg border border-gray-100 self-start">
            <h2 class="text-lg font-bold mb-4">Resumo da Reserva</h2>
            <div class="flex justify-between text-sm mb-2">
                <span>Ingresso Cadeira Superior</span>
                <span class="font-bold">R$ 1.250</span>
            </div>
            <div class="flex justify-between text-sm mb-4">
                <span>Taxa de Serviço (10%)</span>
                <span>R$ 125</span>
            </div>
            <div class="border-t pt-4 mb-6 flex justify-between items-center">
                <span class="font-bold text-lg">Total</span>
                <span class="font-bold text-2xl text-green-600">R$ 1.375</span>
            </div>

            <button class="w-full bg-green-500 hover:bg-green-600 text-white font-extrabold py-4 rounded-xl text-lg shadow-lg transform hover:scale-[1.02] transition mb-4 uppercase">
                Pagar com PIX (Aprovação Imediata)
            </button>

            <p class="text-center text-xs text-red-500 font-medium">
                Sua reserva expira em <span class="underline">09:47</span> minutos
            </p>

            <div class="mt-6 flex items-center justify-center space-x-4 opacity-50 grayscale scale-75">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a2/Logo_Pix.png" class="h-8">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Visa_Inc._logo.svg" class="h-6">
            </div>
        </div>
    </main>

</body>
</html>
