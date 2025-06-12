# 🤖 Colatron2000 (por @gabrielmelo.py) -  
# Google AI direto na sua página

Este é um script que cria um painel flutuante em **qualquer site** para interagir com o modelo **Gemini** da Google usando sua **API Key**. O uso inicial foi pensado para ajudar a “colar” em provas online, mas o painel pode ser usado para diversas outras finalidades.

---

## 🚀 Como usar

Você tem dois métodos simples para usar o painel:

---

### 🧪 Método 1 (Principal e mais fácil): Via Console do Navegador

1. Acesse qualquer site.  
2. Pressione `F12` ou `Ctrl + Shift + I` para abrir o **Console do navegador**.  
3. Cole o código abaixo e pressione **Enter**:

    ```javascript
    (function(){var s=document.createElement('script');s.src='https://colatron2000.github.io/colatron2000/main.js';document.head.appendChild(s);})();
    ```

4. O painel será carregado na tela para você começar a usar.

---

### ✅ Método 2 (Opcional e secundário): Via Bookmark (Favorito)

1. Copie o código abaixo:

    ```javascript
    javascript:(function(){var s=document.createElement('script');s.src='https://colatron2000.github.io/colatron2000/main.js';document.head.appendChild(s);})();
    ```

2. Crie um novo favorito no seu navegador.  
3. No campo **URL** do favorito, cole o código acima.  
4. Acesse qualquer site e clique nesse favorito → o painel será carregado na tela.

---

## 🧠 Como usar o painel Gemini

1. Crie sua API Key em: [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey)  
2. Copie sua API Key e cole no campo indicado no painel.  
3. Faça suas perguntas no campo de texto.  
4. Clique em **Esconder** para minimizar o painel.  
5. Use o botão flutuante no canto inferior direito para abrir novamente.

---

## 📌 Observações

- Sua API Key fica salva localmente (no `localStorage`) para uso contínuo.  
- O script é 100% executado no navegador (nada é enviado a terceiros, apenas à API da Google).

---

## 👨‍💻 Código hospedado em:

🔗 [https://colatron2000.github.io/colatron2000/main.js](https://colatron2000.github.io/colatron2000/main.js)

---

Sinta-se à vontade para clonar, modificar ou sugerir melhorias!
