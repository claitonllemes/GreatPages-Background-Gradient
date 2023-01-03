# GreatPages-Background-Gradient

<a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210368404-216273fb-c930-453e-b32b-e3614872eba3.png" width="100%"/></a><br>

## **Configurações**
O código abaixo adiciona um vídeo ao fundo de um bloco na plataforma Greatpages. Copie e cole no menu de configurações da página.

<br><a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210372197-a1d41894-8acc-470b-ac38-2bd1ee0a4ed9.png" width="100%"/></a><br>


```Html
<style>
  :root {

    --gradient_btn_left: #8b2280;
    --gradient_btn_right: #5423cc;
    --angle: 45deg;

  }

  #e_000000_0_000000000000000000 .c {

    background: -o-linear-gradient(var(--angle), var(--gradient_btn_left), var(--gradient_btn_right));
    background: linear-gradient(var(--angle), var(--gradient_btn_left), var(--gradient_btn_right));
    background: -webkit-linear-gradient(var(--angle), var(--gradient_btn_left), var(--gradient_btn_right));
  }
</style>
```
