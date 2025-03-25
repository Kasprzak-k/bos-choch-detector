# park bos choch detector

Indicador avançado para TradingView que revela a movimentação de "smart money" com métricas exclusivas de performance pós-BOS (Break of Structure).

![BosEX3](https://github.com/user-attachments/assets/d0e451bf-0dc1-4eba-a897-3fd3df23624d)


## 🔍 Recursos Exclusivos

- **Oscilador Smart Money** normalizado (-100 a +100)
- **Detecção precisa de BOS/CHoCH** com confirmação de volume
- **Sistema de porcentagem pós-BOS** que mede:
  - Máxima extensão do movimento
  - Retrações iniciais críticas
  - Força relativa da tendência

- **Divergências profissionais**:
  - Regulares e ocultas (bullish/bearish)
  - Filtros personalizáveis por alcance
  - Visualização com gradiente de cores

- **Zonas institucionais**:
  - Área Premium (compra institucional)
  - Área Discount (venda institucional)

## 🛠 Como Usar

1. Adicione ao TradingView (pine editor)
2. Configure os parâmetros conforme seu estilo:
   - `Smoothing`: Suavização do oscilador
   - `Pivot Length`: Sensibilidade dos pivots
   - `Divergence Range`: Filtro de qualidade

3. Sinalizações visuais:
   - 🔼 Triângulos: BOS
   - 🔵 Círculos: CHoCH
   - 📈 Labels: Performance pós-BOS

## 📈 Cases de Uso

- **Entrada institucional**: Zonas premium/discount
- **Confirmação de tendência**: Sequências de BOS
- **Antecipação de reversões**: Divergências + CHoCH
- **Gerenciamento de risco**: Métricas pós-BOS

## ⚙ Personalização

```pine
// Exemplo de parâmetros para day trading
smoothing = 5
average = 10
pivot_length = 15
enable_hidden_divergence = true
