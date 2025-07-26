# 🏷️ Renomeador de Aldeias - Tribal Wars

Este script permite **renomear aldeias em massa** de forma personalizada e rápida na visão de **Aldeias Combinadas** do Tribal Wars. Ele oferece um painel completo com opções configuráveis e salvamento automático.

## 🔧 Funcionalidades

- ✅ Numeração com dígitos ajustáveis (01, 002, 0001...)
- ✅ Prefixo customizável (Ex: "K45", "ALD", etc)
- ✅ Nome base (texto principal)
- ✅ Contador com início customizado
- ✅ Visualização de exemplo ao vivo
- ✅ Salvamento automático das configurações
- ✅ Botão para resetar todas as opções
- ✅ Interrupção da execução com segurança
- ✅ Totalmente compatível com a interface do Tribal Wars

## 🖥️ Como Usar

1. Acesse a página de **Aldeias Combinadas**:
   ```
   /game.php?screen=overview_villages&mode=combined
   ```

2. Copie e cole o conteúdo do script no **Console do Navegador** (F12 > Aba "Console"):
   ```javascript
   javascript:$.getScript('https://tribalwarstools.github.io/RenomearAldeias/renomearAld.js');
   ```

3. Um painel aparecerá na tela com as seguintes opções:
   - **Dígitos**: quantidade de zeros à esquerda no número.
   - **Prefixo**: adiciona um prefixo ao nome (opcional).
   - **Nome**: define o texto principal (opcional).
   - **Início**: define o número inicial do contador.
   - **Salvar**: armazena suas preferências para uso futuro.
   - **Limpar**: reseta todas as opções salvas e o contador.

4. Clique em **Renomear** para iniciar o processo automático.

5. Um botão "Encerrar Renomeação" será exibido — use-o para parar a qualquer momento.

## 🧪 Exemplo de Nome Gerado

Se configurado para:
- Dígitos: 2
- Prefixo: `K45`
- Nome: `Base`

Resultado:
```
01 K45 Base  
02 K45 Base  
...
```

## 💾 Armazenamento

As configurações e contador são salvos no `localStorage`, mantendo seus dados mesmo ao recarregar a página.

## ⚠️ Requisitos

- Página atual deve estar na visão de **Aldeias Combinadas**.
- Ícones de renomeação (`.rename-icon`) devem estar visíveis.

## 📌 Observações

- O script não afeta aldeias sem o botão de renomear visível.
- É seguro interromper a execução a qualquer momento.

## 📸 Screenshot

Adicione aqui uma imagem do painel (exemplo):

![Painel de Renomeação](./RenomearAld.png)

## 📄 Licença

[MIT License](LICENSE)

---

🛡️ Criado para facilitar a vida de jogadores que gerenciam muitas aldeias manualmente.
