# Terminal-Interativo-com-B-Tree

Este projeto simula comandos básicos de um terminal Unix/Linux utilizando uma estrutura de dados B+ Tree implementada do zero.

---

## Funcionalidades

- `mkdir <nome>`: cria um diretório
- `touch <nome>`: cria um arquivo
- `ls`: lista arquivos e diretórios
- `cd <nome>`: entra no diretório
- `cd ..`: volta ao diretório pai
- `rm <nome>`: remove arquivo ou diretório vazio
- `exit`: encerra o terminal (não pedido no trabalho mas implementado)

---

## Para Executar

1. Certifique-se de ter **Python 3.6 ou superior** instalado.
2. Instale as dependências (somente para o benchmark):

```bash
pip install matplotlib

```

3. Execute o **terminal interativo**:

```bash
python terminal.py
```

4. Execute o **benchmark com matplotlib**:

```bash
python benchmark.py
```

---

## Estrutura dos Arquivos

- `terminal.py`: interface interativa do terminal Unix/Linux simulado.
- `arvore.py`: implementação da estrutura de dados B+ Tree.
- `benchmark.py`: script de benchmark de desempenho com geração de gráfico via `matplotlib`.
- `relatorio.md`: relatório técnico detalhado do projeto.
- `Esquema_visual.png`: esquema visual da estrutura e funcionamento do projeto.
- `Grafico.png`: gráfico de análise de desempenho gerado pelo benchmark.

---

## Relatório Técnico e Análise Visual

- Consulte o relatório técnico completo em [`relatorio.md`](./relatorio.md).
- Imagens de análise:
  - **Esquema visual** (`Esquema_visual.png`):

    ![Esquema Visual](./Esquema_visual.png)

  - **Gráfico de desempenho** (`Grafico.png`):

    ![Gráfico de Desempenho](./Grafico.png)
