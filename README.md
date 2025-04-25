# 🪙 CriptoApp

Aplicativo web desenvolvido em **React** com **Vite**, que consome dados da **CoinCap API** para exibir informações de criptomoedas em tempo real.

![Badge React](https://img.shields.io/badge/react-18.2.0-blue)
![Badge Vite](https://img.shields.io/badge/vite-5.2.0-yellow)
![Badge License](https://img.shields.io/badge/license-MIT-green)

---

## 📱 Funcionalidades

- ✅ Lista de criptomoedas com nome, símbolo, imagem e valor atual.
- ✅ Ordenação por valor de mercado.
- ✅ Interface limpa e responsiva.
- ✅ Atualização dos dados via CoinCap API.

---

## 📸 Captura de Tela

| Lista de Moedas                                                                                           |
| --------------------------------------------------------------------------------------------------------- |
| ![tela](https://github.com/antoni0jsneto/criptoapp/assets/123251330/bc25795e-c49f-4d2d-9e7a-62d6344bda17) |

---

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Axios](https://axios-http.com/)
- [CoinCap API](https://pro.coincap.io)

---

## 🛠️ Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/antoni0jsneto/criptoapp.git
   cd criptoapp
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   # ou
   yarn
   ```

3. **Configure a variável de ambiente:**

   Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

   ```
   VITE_COINCAP_API_KEY=sua_api_key_aqui
   ```

   Para obter a **API KEY**:

   - Acesse: [https://pro.coincap.io](https://pro.coincap.io)
   - Crie sua conta e faça o login
   - Clique no botão **"Add New Key"**
   - Copie a chave gerada e cole no seu `.env`

4. **Execute o projeto:**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

---

## 📁 Estrutura de Pastas

```
criptoapp/
│
├── components/
│   └── CoinItem.jsx   # Componente que exibe os dados da moeda
│
├── services/
│   └── api.js         # Configuração do Axios com a API
│
├── App.jsx            # Componente principal
└── ...
```

---

## 📌 To-Do

- [ ] Tela de detalhes da criptomoeda
- [ ] Filtro por nome ou símbolo
- [ ] Gráfico de variação de preços

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido por **Antônio Neto** 🚀  
[LinkedIn](https://www.linkedin.com/in/antoni0jsneto) • [GitHub](https://github.com/antoni0jsneto)

---

⭐ Se você gostou do projeto, deixe uma estrela no repositório!
