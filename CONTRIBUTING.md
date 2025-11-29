# Guia de Contribuição

Obrigado por considerar contribuir com o Gerador de Senhas Seguro! 🎉

## Como Contribuir

### Reportando Bugs

Se você encontrou um bug:

1. Verifique se o bug já não foi reportado nas [Issues](https://github.com/seu-usuario/gerador-senhas/issues)
2. Se não foi reportado, crie uma nova issue com:
   - Título descritivo
   - Descrição clara do problema
   - Passos para reproduzir
   - Comportamento esperado vs. atual
   - Screenshots (se aplicável)
   - Informações do ambiente (navegador, OS, etc.)

### Sugerindo Melhorias

Para sugerir novas funcionalidades:

1. Verifique se a sugestão já não existe nas Issues
2. Crie uma issue com:
   - Título claro da funcionalidade
   - Descrição detalhada
   - Casos de uso
   - Benefícios esperados

### Enviando Pull Requests

1. **Fork o repositório**
   ```bash
   git clone https://github.com/seu-usuario/gerador-senhas.git
   cd gerador-senhas
   ```

2. **Crie uma branch para sua feature**
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```

3. **Faça suas alterações**
   - Siga o padrão de código existente
   - Adicione comentários quando necessário
   - Teste todas as funcionalidades

4. **Commit suas mudanças**
   ```bash
   git add .
   git commit -m "feat: adiciona nova funcionalidade"
   ```

5. **Push para o repositório**
   ```bash
   git push origin feature/nova-funcionalidade
   ```

6. **Abra um Pull Request**
   - Descreva claramente o que foi alterado
   - Referencie issues relacionadas (se houver)
   - Adicione screenshots se aplicável

## Padrões de Código

### JavaScript
- Use nomes descritivos para variáveis e funções
- Mantenha funções pequenas e focadas
- Comente código complexo
- Siga o estilo existente

### CSS
- Use variáveis CSS para cores
- Mantenha seletores específicos
- Organize por seções
- Use nomes semânticos para classes

### HTML
- Use HTML semântico
- Mantenha estrutura limpa
- Adicione atributos alt em imagens
- Use atributos ARIA quando necessário

## Convenções de Commit

Use mensagens de commit descritivas:

- `feat:` Nova funcionalidade
- `fix:` Correção de bug
- `docs:` Documentação
- `style:` Formatação, espaços, etc.
- `refactor:` Refatoração de código
- `test:` Testes
- `chore:` Tarefas de manutenção

Exemplo:
```
feat: adiciona modo de tema claro/escuro
fix: corrige cálculo de entropia para senhas curtas
docs: atualiza README com novas funcionalidades
```

## Testes

Antes de submeter:

- [ ] Teste em diferentes navegadores (Chrome, Firefox, Safari, Edge)
- [ ] Teste em dispositivos móveis
- [ ] Verifique se não quebrou funcionalidades existentes
- [ ] Teste casos extremos

## Perguntas?

Se tiver dúvidas, abra uma issue com a tag `question`.

Obrigado por contribuir! 🚀

