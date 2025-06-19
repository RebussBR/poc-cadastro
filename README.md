# 🧾 Validador de Dados - Front-end Simples

Este projeto é uma página HTML interativa que permite ao usuário validar e preencher dados pessoais de forma segura e automatizada. Ideal para empresas que desejam coletar ou atualizar cadastros de clientes, parceiros ou colaboradores sem fricção.

---

## 🚀 Funcionalidades

- ✅ Validação de **CPF** com dígitos verificadores
- ✅ Validação de **telefone** no formato nacional (DDD + número)
- ✅ Busca automática de endereço via **CEP** usando API pública do ViaCEP
- ✅ Seleção de **banco** via dropdown (com códigos Febraban)
- ✅ Campos dinâmicos de **agência e conta bancária**
- ✅ Validação inteligente de **agência conforme o banco**
- ✅ Entrada livre de **chave PIX**
- 💡 Preparado para integração com back-end (API, Dataverse, SQL etc.)

---

## 🖥️ Como usar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` diretamente no navegador
3. Preencha CPF e telefone para buscar dados
4. Digite o CEP para preencher endereço automaticamente
5. Escolha o banco para exibir campos de agência e conta
6. Clique em **Confirmar** para simular o envio

---

## 🌐 Deploy via GitHub Pages

Para publicar esta página online:

1. Crie um repositório público
2. Faça upload do arquivo `index.html`
3. Vá em **Settings > Pages**
4. Em **Source**, selecione a branch `main` e pasta `/ (root)`
5. Acesse a URL gerada: `https://SEU_USUARIO.github.io/NOME-REPOSITORIO/`

---

## 📦 Estrutura do Projeto

├── index.html # Página com lógica e validações embutidas
├── README.md # Documentação
└── [opcional] CSS/JS externos (tudo inline por padrão)


---

## 🛡️ Segurança e LGPD

> Esta versão é apenas front-end. Para estar em conformidade com a LGPD, recomenda-se:

- Proteger o back-end com autenticação
- Criptografar dados sensíveis em trânsito e em repouso
- Incluir consentimento do usuário
- Auditar modificações

---

## 🛠️ Próximos passos (roadmap)

- [ ] Integração com API real (Dataverse, Azure SQL, etc.)
- [ ] Autenticação por token ou Azure AD B2C
- [ ] Salvamento de dados via formulário dinâmico
- [ ] Validação de conta com dígito verificador por banco
- [ ] Upload de documentos (opcional)

---

## ✨ Exemplo ao vivo

> (adicione aqui o link do GitHub Pages quando publicar)

---

## 👨‍💻 Autor

**Pedro Miguel Donalonso Corrêa**  
IT Lead @ Rebuss | Business Intelligence & Automação  

---
