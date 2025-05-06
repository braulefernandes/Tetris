
# 🎮 Tetris em Java

Este é um projeto do jogo **Tetris** desenvolvido em **Java**, com uma estrutura modular de classes, ranking de jogadores e sons personalizados.

## 📦 Estrutura do Projeto

```
Tetris/
├── br/com/mvbos/lgj/         # Código-fonte do jogo
│   ├── base/                 # Classes utilitárias e estruturas base
│   ├── Jogo.java             # Classe principal do jogo
│   └── ...                   # Outras classes do jogo
├── som/                      # Sons do jogo
│   ├── EliminacaoLinha.wav
│   ├── GameOver.wav
│   └── MoviPecas.mid
├── Ranking.txt               # Arquivo com ranking dos jogadores
```

## 🚀 Como Executar

1. Certifique-se de ter o **Java JDK 8+** instalado.
2. Compile os arquivos `.java` dentro da pasta `Tetris/br/com/mvbos/lgj/`.
3. Execute a classe principal `Jogo.java`.

```bash
javac Tetris/br/com/mvbos/lgj/*.java Tetris/br/com/mvbos/lgj/base/*.java
java br.com.mvbos.lgj.Jogo
```

> Obs: O projeto não usa bibliotecas externas nem sistemas de build (como Maven/Gradle).

## 🔊 Funcionalidades

- ✅ Movimento e rotação de peças
- ✅ Eliminação de linhas
- ✅ Ranking de jogadores salvo em `Ranking.txt`
- ✅ Sons de movimento e game over

## 🛠 Tecnologias

- **Java SE**
- Manipulação de arquivos para ranking
- Áudio com `javax.sound.sampled` e `javax.sound.midi`

---
#### Desenvolvido por Cícero Braule ✨
