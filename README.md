# BankFlow Demo - Plataforma Financeira Completa

**Demo de Dashboard Financeiro com suporte a múltiplos bancos brasileiros**

🔗 Link do Projeto: https://github.com/callonlogin-ops/finance-dashboard-demo

## 📋 Funcionalidades

### ✅ Bancos Suportados
- Bradesco
- Itaú
- Banco do Brasil (BB)
- Santander
- Caixa Econômica Federal
- Nubank
- Neon
- PagSeguro
- Win Transfer
- Wink
- Spraynt

### 💳 Operações Bancárias
- ✅ PIX (com QR Code)
- ✅ TED
- ✅ DOC
- ✅ Boleto
- ✅ Cheque
- ✅ REF
- ✅ Transferência
- ✅ Depósito
- ✅ Saque
- ✅ Abertura de Conta

### 📊 Recursos Avançados
- 💰 Saldo com Empréstimo
- 📅 Agendamento de Transferências
- 📄 Exportação em PDF
- 🔄 Estorno e Reembolso
- 🔐 Contestação de PIX
- 🔗 Link de Pagamento
- 📱 Responsivo
- 🌙 Interface moderna

## 🚀 Como Usar

1. **Clone o repositório**
```bash
git clone https://github.com/callonlogin-ops/finance-dashboard-demo.git
cd finance-dashboard-demo
```

2. **Abra no navegador**
```bash
Abra o arquivo index.html no seu navegador
```

3. **Ou use um servidor local**
```bash
python -m http.server 8000
# ou
npx http-server
# ou
php -S localhost:8000
```

## 📂 Estrutura do Projeto

```
finance-dashboard-demo/
├── index.html              # Página principal
├── css/
│   ├── style.css          # Estilos principais
│   └── responsive.css     # Estilos responsivos
├── js/
│   ├── app.js             # Lógica principal
│   ├── banks.js           # Banco de dados de bancos
│   ├── transactions.js    # Gerenciamento de transações
│   ├── pix.js             # Módulo PIX/QR Code
│   ├── pdf.js             # Exportação PDF
│   └── utils.js           # Funções utilitárias
├── assets/
│   ├── logos/             # Logos dos bancos
│   └── icons/             # Ícones
├── data/
│   └── mock-data.json     # Dados simulados
└── README.md
```

## 🎯 Funcionalidades Detalhadas

### PIX e QR Code
- Gera QR Code simulado
- Cópia de chave PIX
- Transferência instantânea

### Agendamento
- Agende transferências para datas futuras
- Receba notificação
- Modifique ou cancele operações agendadas

### Exportação PDF
- Comprovante de operação
- Extrato bancário
- Recibos

### Contestação de PIX
- Solicite contestação em 60 dias
- Acompanhe status
- Receba reembolso

## 💻 Tecnologias
- HTML5
- CSS3 (Flexbox + Grid)
- JavaScript (Vanilla)
- jsPDF (Exportação)
- QRCode.js (QR Code)

## 📄 Licença
MIT

## 👨‍💻 Autor
callonlogin-ops

---

⭐ Se gostou, deixe uma star!
