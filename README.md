# 🌱 Plantas vs. Zumbis - Computação Gráfica

Jogo desenvolvido em **Python** utilizando **OpenGL** e **GLFW**, como parte do trabalho prático da disciplina de **Computação Gráfica**.
Inspirado no clássico *Plants vs Zombies*, o objetivo do jogo é **plantar defesas** para impedir que os **zumbis** alcancem o final do gramado.

---

## 🚀 Funcionalidades principais

* 🌾 **Tabuleiro interativo**: o jogador pode navegar pelo gramado com as setas do teclado.
* 🌻 **Plantação dinâmica**: ao pressionar **Enter**, uma planta é posicionada no local selecionado.
* 🔫 **Disparo automático**: as plantas disparam projéteis a cada intervalo de tempo.
* 🧟 **Zumbis animados**: os inimigos se movem lentamente da direita para a esquerda.
* 💥 **Detecção de colisão**: projéteis atingem os zumbis, que perdem “vida” até serem eliminados.

---

## ⚙️ Tecnologias utilizadas

* **Python 3**
* **OpenGL (PyOpenGL)**
* **GLFW**
* **NumPy**

---

## 🕹️ Como jogar

### ✅ Requisitos

Instale as dependências:

```bash
pip install PyOpenGL PyOpenGL_accelerate glfw numpy
```

### ▶️ Executar o jogo

```bash
python jogo.py
```

### 🎯 Controles

| Tecla | Ação                           |
| ----- | ------------------------------ |
| ← / → | Move a seleção horizontalmente |
| ↑ / ↓ | Move a seleção verticalmente   |
| Enter | Planta uma nova defesa         |
| ESC   | Fecha o jogo                   |

---

## 🧩 Estrutura do projeto

```
.
├── jogo.py          # Loop principal e lógica de interação
├── plantas.py       # Classe Planta e Projeteis
├── zumbi.py         # Classe Zumbi
└── README.md
```

---

## 🧠 Conceitos de Computação Gráfica aplicados

* Projeção ortográfica com `glOrtho`
* Transformações geométricas (`glTranslatef`, `glRotatef`, `glScale`)
* Modelagem de objetos 2D com polígonos
* Controle de cor e renderização
* Animação por atualização de quadros (`time.sleep`, `glfw.poll_events`)

---

## 👥 Equipe

| Nome           | Função / Responsabilidade                               |
| -------------- | ------------------------------------------------------- |
| Evanildo       | Lógica principal, interface e sistema de seleção        |
| Mahatma        | Implementação dos zumbis e colisões                     |
| Victor         | Controle de plantas e projeteis                         |

---

## 💡 Melhorias futuras

* Adicionar novos tipos de plantas e zumbis
* Implementar pontuação e tela de game over
* Inserir sons e texturas melhores
* Criar um menu inicial com opções

---

## 🏫 Sobre o projeto

Desenvolvido como atividade prática da disciplina **Computação Gráfica** do curso de Ciência da Computação da Universidade Federal do Ceará - Campus Russas.
O objetivo foi aplicar transformações geométricas, renderização 2D e manipulação de eventos via GLFW.

