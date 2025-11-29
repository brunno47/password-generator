# 🔐 Gerador de Senhas Seguro

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

Um gerador de senhas moderno, seguro e completo com sistema de autenticação, análise de força e histórico personalizado.

[Demo](#) • [Documentação](#) • [Reportar Bug](#)

</div>

---

## ✨ Características

### 🔒 Segurança
- **Geração criptograficamente segura** usando `crypto.getRandomValues()`
- **Sistema de autenticação** completo com registro e login
- **Histórico isolado por usuário** - cada conta tem seu próprio histórico
- **Análise de força em tempo real** com cálculo de entropia

### 🎨 Interface Moderna
- **Design glassmorphism** com efeitos visuais elegantes
- **Animações suaves** e transições fluidas
- **Responsivo** - funciona perfeitamente em desktop e mobile
- **Tema escuro** otimizado para os olhos

### 🚀 Funcionalidades Avançadas
- **3 Modos de geração:**
  - 🔹 Normal - Senhas aleatórias completas
  - 🔹 Memorável - Combinação de palavras fáceis de lembrar
  - 🔹 PIN - Apenas números para códigos PIN

- **Opções personalizáveis:**
  - Comprimento configurável (4-64 caracteres)
  - Incluir/excluir maiúsculas, minúsculas, números e símbolos
  - Excluir caracteres similares (0, O, 1, l, I)
  - Gerar múltiplas senhas de uma vez

- **Estatísticas detalhadas:**
  - Entropia em bits
  - Tempo estimado para quebrar a senha
  - Número de combinações possíveis
  - Análise completa de padrões e vulnerabilidades

- **Histórico e exportação:**
  - Armazenamento local de até 50 senhas
  - Exportar em TXT, JSON ou CSV
  - Importar histórico de arquivos
  - Limpar histórico com confirmação

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com animações
- **JavaScript (Vanilla)** - Lógica e interatividade
- **LocalStorage API** - Armazenamento local de dados
- **Web Crypto API** - Geração segura de números aleatórios

## 📦 Instalação

### Pré-requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desenvolvimento)

### Passos

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/gerador-senhas.git
   cd gerador-senhas
   ```

2. **Abra o projeto**
   - Opção 1: Abra `index.html` diretamente no navegador
   - Opção 2: Use um servidor local:
     ```bash
     # Com Python
     python -m http.server 8000
     
     # Com Node.js (http-server)
     npx http-server
     
     # Com PHP
     php -S localhost:8000
     ```

3. **Acesse no navegador**
   - Abra `http://localhost:8000` (se usar servidor)
   - Ou abra `index.html` diretamente

## 🎯 Como Usar

### Primeiro Acesso

1. **Criar Conta**
   - Clique em "Criar conta"
   - Preencha nome, email e senha
   - A senha deve ter no mínimo 6 caracteres
   - Um indicador mostra a força da senha em tempo real

2. **Fazer Login**
   - Digite seu email e senha
   - Clique em "Entrar"
   - Sua sessão será mantida automaticamente

### Gerando Senhas

1. **Escolha o modo:**
   - **Normal**: Para senhas aleatórias completas
   - **Memorável**: Para senhas fáceis de lembrar
   - **PIN**: Para códigos numéricos

2. **Configure as opções:**
   - Ajuste o comprimento com o slider
   - Selecione os tipos de caracteres desejados
   - Ative opções avançadas se necessário

3. **Gere a senha:**
   - Clique em "Gerar Senha"
   - A senha aparecerá com animação de digitação
   - Use o botão de copiar para copiar rapidamente

4. **Analise a segurança:**
   - Veja a força da senha na barra de progresso
   - Confira as estatísticas (entropia, tempo estimado)
   - Acesse a aba "Análise" para detalhes completos

### Gerenciando Histórico

- **Visualizar**: Acesse a aba "Histórico"
- **Copiar**: Clique no ícone 📋 ao lado da senha
- **Remover**: Clique no ícone 🗑️ para deletar
- **Exportar**: Use a aba "Exportar" para salvar em diferentes formatos
- **Importar**: Importe senhas de arquivos anteriores

## 📁 Estrutura do Projeto

```
gerador-senhas/
│
├── index.html          # Estrutura HTML principal
├── style.css           # Estilos e animações
├── script.js           # Lógica e funcionalidades
├── README.md           # Documentação do projeto
└── .gitignore          # Arquivos ignorados pelo Git
```

## 🔐 Segurança

### Armazenamento
- **Senhas de usuário**: Codificadas em Base64 (apenas para demonstração)
- **Histórico de senhas**: Armazenado localmente no navegador
- **Sessões**: Gerenciadas via LocalStorage

### ⚠️ Aviso Importante
Este projeto é uma demonstração educacional. Para uso em produção:
- Use hash seguro (bcrypt, Argon2) para senhas
- Implemente autenticação com tokens JWT
- Use HTTPS obrigatório
- Considere criptografia adicional para dados sensíveis

## 🎨 Personalização

### Cores
As cores podem ser personalizadas no arquivo `style.css` através das variáveis CSS:

```css
:root {
    --primary: #6366f1;
    --secondary: #8b5cf6;
    --success: #10b981;
    --warning: #f59e0b;
    --danger: #ef4444;
}
```

### Animações
Todas as animações podem ser ajustadas nos `@keyframes` do CSS.

## 🐛 Problemas Conhecidos

- Nenhum problema conhecido no momento

## 🚧 Melhorias Futuras

- [ ] Modo claro/escuro
- [ ] Geração de senhas baseadas em frases
- [ ] Integração com gerenciadores de senha
- [ ] Sincronização em nuvem
- [ ] Compartilhamento seguro de senhas
- [ ] API REST para integração
- [ ] Testes automatizados

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

### Guia de Contribuição

- Siga o padrão de código existente
- Adicione comentários quando necessário
- Teste suas mudanças antes de submeter
- Atualize a documentação se necessário

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Seu Nome**

- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: seu.email@exemplo.com

## 🙏 Agradecimentos

- Inspiração de design moderno
- Comunidade open source
- Todos os contribuidores

## 📊 Estatísticas do Projeto

![GitHub stars](https://img.shields.io/github/stars/seu-usuario/gerador-senhas?style=social)
![GitHub forks](https://img.shields.io/github/forks/seu-usuario/gerador-senhas?style=social)
![GitHub issues](https://img.shields.io/github/issues/seu-usuario/gerador-senhas)
![GitHub pull requests](https://img.shields.io/github/issues-pr/seu-usuario/gerador-senhas)

---

<div align="center">

**⭐ Se este projeto foi útil, considere dar uma estrela! ⭐**

Feito com ❤️ e ☕

</div>

