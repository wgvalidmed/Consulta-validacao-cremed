# Validador de Consultas Médicas

Este projeto oferece duas páginas para validação de documentos médicos, ideais para uso por clínicas, consultórios ou serviços de telemedicina.

## 📂 Conteúdo

- `validador.html`: Página para validar documentos via código único (gerado pelo sistema).
- `validacao-publica.html`: Página pública onde pacientes ou terceiros podem validar manualmente com nome, CRM e nome do paciente.

---

## 🌐 Hospedagem com GitHub Pages

Você pode hospedar este sistema gratuitamente no GitHub Pages:

### Passo a passo:

1. Faça upload dos arquivos para um repositório GitHub.
2. Vá até o menu `Settings` do repositório.
3. Em **Pages**, configure a **branch principal** (ex: `main`) e o **diretório raiz** (`/root`).
4. O GitHub irá gerar um link como:

5. ---

## ✅ Exemplos de uso

- **Validação por código**:  
  Acesse o link:  
  `https://seusite.com/validador.html?codigo=ABC123`

- **Validação manual (clientes)**:  
  Acesse:  
  `https://seusite.com/validacao-publica.html`

---

## 🛠 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (sem frameworks)
- `localStorage` para simular banco de dados local

---

## 🔒 Observações

> Este sistema usa `localStorage`, ou seja, funciona localmente no navegador. Para ambientes de produção real (com banco de dados e controle de acesso), é recomendável usar uma API ou servidor.

---

© 2025 - Sistema de Validação de Documentos Médicos
