# FIND WHAT

**FIND WHAT** é um jogo multiplayer local/online desenvolvido em Unreal Engine 5. O objetivo principal é encontrar itens específicos escondidos em meio a uma multidão de objetos espalhados por fases instanciadas dinamicamente.

---

## Sobre o Jogo

Cada partida apresenta desafios únicos onde os itens são instanciados individualmente para cada jogador, garantindo uma experiência imersiva e sem interferência visual dos adversários no mesmo espaço de minijogo.

### Destaques

- **Minijogos Instanciados:** Carregamento e descarregamento dinâmico de níveis no cliente.
- **Interação Física Local:** Coleta e busca com física processada localmente para melhor tempo de resposta.
- **Multiplayer Sincronizado:** Suporte a múltiplos jogadores via cliente/servidor com isolamento de cenários locais para evitar desyncs.

---

## Tecnologias Utilizadas

- **Engine:** Unreal Engine 5
- **Linguagem / Scripting:** Blueprints Visual Scripting
- * **Rede & Multiplayer:** Host + Cliente rodando em instâncias Standalone, utilizando Client RPCs e física local isolada para os minijogos.
- **Arquitetura de Níveis:** Dynamic Level Streaming

---

## Como Executar o Projeto

### Pré-requisitos
- Unreal Engine 5.0 ou superior
- Computador com suporte a DirectX 11/12

### Executando no Editor

1. Clone o repositório:
   ```bash
   git clone [https://github.com/Edu-Dev12/Find-What.git](https://github.com/Edu-Dev12/Find-What.git)
2. Abra o arquivo .uproject no Unreal Engine.
3. No Editor, navegue até a pasta de UI e abra o mapa de menu principal.
4. Nas configurações de Play, defina o número de jogadores para 2 ou mais e selecione o modo Standalone.
5. Clique em Play.
