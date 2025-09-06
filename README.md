<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kwanza Invest - Invista em Kuanzas Diariamente</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #00509D;
            color: white;
            padding: 1.5rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .banner {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }
        .banner h2 {
            color: #00509D;
            margin-bottom: 1rem;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 2rem 0;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }
        th, td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid #eee;
        }
        th {
            background: #00509D;
            color: white;
            font-weight: 600;
        }
        tr:hover {
            background: #f8f9fa;
        }
        .form-container {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }
        .form-container h3 {
            margin-bottom: 1.5rem;
            color: #00509D;
        }
        input, textarea, button {
            width: 100%;
            padding: 0.8rem;
            margin: 0.5rem 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        button {
            background: #00509D;
            color: white;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.3s;
        }
        button:hover {
            background: #003d7a;
        }
        .iban-section {
            background: #e3f2fd;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            border-left: 5px solid #00509D;
        }
        footer {
            text-align: center;
            padding: 2rem;
            background: #333;
            color: white;
            margin-top: 3rem;
        }
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            table, .form-container, .iban-section {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>🇰🇼 KWANZA INVEST</h1>
        <p>Invista em Kuanzas e receba rentabilidade diária</p>
    </header>

    <div class="container">

        <section class="banner">
            <h2>💰 Comece a Investir Hoje Mesmo!</h2>
            <p>Escolha seu plano, faça seu pagamento diário e acompanhe seus rendimentos crescerem.</p>
        </section>

        <section>
            <h2>📈 Planos de Investimento Disponíveis</h2>
            <table>
                <tr>
                    <th>Plano</th>
                    <th>Valor Mínimo</th>
                    <th>Rentabilidade Diária</th>
                    <th>Prazo Mínimo</th>
                    <th>Descrição</th>
                </tr>
                <tr>
                    <td>Plano Bronze</td>
                    <td>5.000 Kz</td>
                    <td>1,5%</td>
                    <td>7 dias</td>
                    <td>Ideal para iniciantes</td>
                </tr>
                <tr>
                    <td>Plano Prata</td>
                    <td>20.000 Kz</td>
                    <td>2,0%</td>
                    <td>15 dias</td>
                    <td>Retorno moderado</td>
                </tr>
                <tr>
                    <td>Plano Ouro</td>
                    <td>50.000 Kz</td>
                    <td>2,5%</td>
                    <td>30 dias</td>
                    <td>Alta rentabilidade</td>
                </tr>
                <tr>
                    <td>Plano Diamante</td>
                    <td>200.000 Kz</td>
                    <td>3,0%</td>
                    <td>60 dias</td>
                    <td>Exclusivo para grandes valores</td>
                </tr>
            </table>
        </section>

        <section class="iban-section">
            <h3>🏦 IBAN para Pagamentos e Recebimentos</h3>
            <p><strong>IBAN da Plataforma:</strong><br>
               <code>AO97 0006 0000 1234 5678 9012 3</code><br>
               <em>Titular: Kwanza Invest Lda</em>
            </p>
            <p>Após efetuar seu pagamento, envie o comprovante para nosso WhatsApp: <strong>+244 9XX XXX XXX</strong></p>
        </section>

        <section class="form-container">
            <h3>📝 Quero Abrir Minha Conta!</h3>
            <form action="https://formspree.io/f/your-form-id" method="POST">
                <input type="text" name="nome" placeholder="Nome Completo" required>
                <input type="email" name="email" placeholder="Email" required>
                <input type="tel" name="telefone" placeholder="Telefone (com DDD)">
                <textarea name="iban" placeholder="Informe seu IBAN para recebimento" rows="2" required></textarea>
                <button type="submit">Enviar Cadastro</button>
            </form>
            <p style="margin-top: 1rem; font-size: 0.9rem; color: #666;">
                Após envio, nossa equipe entrará em contato em até 24h para validar sua conta.
            </p>
        </section>

    </div>

    <footer>
        <p>🇰🇼 Kwanza Invest © 2025 — Todos os direitos reservados.</p>
        <p>Investimento sujeito a riscos. Consulte nossos termos.</p>
    </footer>

</body>
</html>
