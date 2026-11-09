<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet Bites - E-commerce & Delivery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #faf6f0;
            color: #3b2f2f;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            background-color: #d4bda8;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 24px;
            letter-spacing: 2px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        section {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        h2 {
            font-size: 18px;
            border-bottom: 2px solid #faf6f0;
            padding-bottom: 8px;
            margin-top: 0;
        }
        .produtos-grid {
            display: grid;
            gap: 15px;
        }
        .produto-card {
            border: 1px solid #d4bda8;
            padding: 15px;
            border-radius: 6px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .preco {
            font-weight: bold;
            color: #2b8a3e;
        }
        button {
            background-color: #5c4033;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #3b2f2f;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            padding: 8px 0;
            border-bottom: 1px solid #faf6f0;
            display: flex;
            justify-content: space-between;
        }
        .total {
            font-weight: bold;
            font-size: 18px;
            text-align: right;
        }
        .checkout, .avaliacao-secao {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-top: 15px;
        }
        textarea, select {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .btn-finalizar {
            background-color: #2b8a3e;
            font-size: 16px;
        }
        .info-aluno {
            font-size: 12px;
            color: #666;
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>GOURMET BITES 🧁☕</h1>
        <p>Cupcakes artesanais e cafés especiais</p>
    </header>

    <main class="container">
        <!-- Secção do Cardápio -->
        <section class="cardapio">
            <h2>Cardápio Digital</h2>
            <div class="produtos-grid">
                <div class="produto-card">
                    <div>
                        <h3>Cupcake Especial de Chocolate</h3>
                        <p class="preco">R$ 12,90</p>
                    </div>
                    <button onclick="adicionarCarrinho('Cupcake de Chocolate', 12.90)">Adicionar</button>
                </div>
                <div class="produto-card">
                    <div>
                        <h3>Café Expresso Gourmet</h3>
                        <p class="preco">R$ 7,50</p>
                    </div>
                    <button onclick="adicionarCarrinho('Café Expresso', 7.50)">Adicionar</button>
                </div>
            </div>
        </section>

        <!-- Secção do Carrinho -->
        <section class="carrinho-secao">
            <h2>Carrinho de Compras</h2>
            <ul id="lista-carrinho">
                <li class="vazio">O carrinho está vazio.</li>
            </ul>
            <p class="total">Total: R$ <span id="valor-total">0,00</span></p>

            <div class="checkout">
                <select id="pagamento">
                    <option value="pix">Pix</option>
                    <option value="cartao">Cartão de Crédito</option>
                </select>
                <button class="btn-finalizar" onclick="finalizarPedido()">Confirmar Pedido</button>
            </div>
        </section>

        <!-- Painel de Avaliações -->
        <section class="avaliacao-secao">
            <h2>Avaliar Pedido</h2>
            <textarea id="comentario-aval" placeholder="Deixe o seu comentário sobre o atendimento..."></textarea>
            <button onclick="enviarAvaliacao()">Enviar Avaliação</button>
        </section>

        <div class="info-aluno">
            <p>PIT II - Diego Perozini Ambrozio (RGM: 37123092) | Sistemas de Informação</p>
        </div>
    </main>

    <script>
        let carrinho = [];
        let total = 0;

        function adicionarCarrinho(nome, preco) {
            carrinho.push({ nome, preco });
            atualizarCarrinho();
        }

        function atualizarCarrinho() {
            const lista = document.getElementById('lista-carrinho');
            const spanTotal = document.getElementById('valor-total');
            
            lista.innerHTML = '';
            total = 0;

            if (carrinho.length === 0) {
                lista.innerHTML = '<li class="vazio">O carrinho está vazio.</li>';
            } else {
                carrinho.forEach((item) => {
                    total += item.preco;
                    let li = document.createElement('li');
                    li.innerHTML = `${item.nome} <span>R$ ${item.preco.toFixed(2)}</span>`;
                    lista.appendChild(li);
                });
            }

            spanTotal.textContent = total.toFixed(2);
        }

        function finalizarPedido() {
            if (carrinho.length === 0) {
                alert('O carrinho está vazio!');
                return;
            }
            const forma = document.getElementById('pagamento').value;
            alert(`Compra finalizada com sucesso via ${forma.toUpperCase()}!`);
            carrinho = [];
            atualizarCarrinho();
        }

        function enviarAvaliacao() {
            const texto = document.getElementById('comentario-aval').value;
            if (texto.trim() === '') {
                alert('Por favor, escreva um comentário antes de enviar.');
                return;
            }
            alert('Avaliação enviada com sucesso! Obrigado pelo feedback.');
            document.getElementById('comentario-aval').value = '';
        }
    </script>
</body>
</html>
