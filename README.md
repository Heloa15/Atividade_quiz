# 📚 Quiz em Flutter

Aplicativo simples de **quiz educacional** desenvolvido em **Flutter**, onde o usuário responde perguntas de múltipla escolha com imagens e recebe a pontuação ao final.

---

# 🎯 Como Funciona

1. O usuário inicia o quiz
2. Uma pergunta é exibida com alternativas
3. O usuário escolhe uma resposta
4. O sistema verifica se está correta
5. Ao final, a pontuação é mostrada

Fluxo:

```
Pergunta → Resposta → Próxima → Resultado
```

---

# ✨ Funcionalidades

* Perguntas de múltipla escolha
* Suporte a imagens (URL ou Base64)
* Verificação automática da resposta
* Contagem de pontos
* Resultado final do quiz

---

# 🧰 Tecnologias Utilizadas

* Flutter
* Dart
* JSON

---

# 🚀 Como Executar

```bash
flutter pub get
```

---

# ➕ Como Adicionar Perguntas

Adicione um novo item na lista `perguntas`:

```json
{
  "ilustracao": "https://link-da-imagem.com"
  "pergunta": "Exemplo de pergunta",
  "respostas": ["A", "B", "C", "D"],
  "correta": 2,
}
```



# 👨‍💻 Autor

Projeto desenvolvido para fins educacionais em Flutter.
