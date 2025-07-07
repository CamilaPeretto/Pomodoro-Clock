# ⏰ PomoClock – Seu Tempo, Sua Regra

PomoClock é um aplicativo completo de gerenciamento de tempo, construído com **Vue.js 3 via CDN**, HTML5 e CSS3, projetado para ser intuitivo, responsivo e funcional. Ele combina diferentes modos de controle do tempo em uma só aplicação: relógio digital, analógico, cronômetro, temporizador, alarme e técnica Pomodoro.

---

## 💡 Motivação

Num mercado acelerado, a gestão do tempo é uma das soft skills mais valorizadas. Esse projeto nasceu da vontade de reunir em um único app **ferramentas reais que usamos no dia a dia** como devs, estudantes e pessoas multitarefa, tudo com um visual leve, elegante e fácil de usar.

---

## ✨ Funcionalidades

- 🕒 **Relógio Digital:** exibe o horário atual com precisão, atualizando a cada segundo.
- 🕰️ **Relógio Analógico:** com ponteiros funcionais e marcações de horas dinâmicas.
- ⏱️ **Cronômetro:** inicia, pausa e reseta o tempo contado.
- ⏳ **Temporizador:** insira minutos e segundos, e o app avisa quando o tempo acabar.
- 🔔 **Alarme:** configure um horário futuro e receba um alerta visual e sonoro.
- 🍅 **Pomodoro:** 25 minutos de foco + 5 de pausa, com troca automática, som e mensagens amigáveis.

---

## 🧠 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| **Vue.js 3 (via CDN)** | Utilizado com Composition API (`ref`, `computed`, `onMounted`) para reatividade e modularidade. |
| **HTML5 + CSS3** | Layout semântico, responsivo e com foco em UX acessível. |
| **Som** | Alertas sonoros adicionados ao Pomodoro, Temporizador e Alarme (com preload). |

---

## 🧩 Arquitetura do Projeto

O projeto foi estruturado em **um único arquivo HTML** para facilitar deploy rápido. Ele possui:

- `index.html` – App completo com todos os modos.
- `style.css` – Estilo modular baseado em variáveis (`:root`) e design responsivo.
- `som/Ding-sound-effect.wav` – Arquivo de som usado para avisos (alarme, timer, pomodoro).
- `img/tecnica-pomodoro.png` – Arquivo de imagem usado no favicon.

---

## 🛠️ Clean Code na Prática

- Componentização via funções e estados isolados
- Comentários claros e semântico
- Uso adequado de `ref`, `computed`, `setInterval` e `clearInterval`
- Lógica separada por contexto (pomodoro, temporizador, etc.)
- Boas práticas de acessibilidade e UX (botões, inputs, feedbacks visuais)

---

## 📱 Responsividade

O layout foi feito para se adaptar a diferentes tamanhos de tela: mobile, tablet e desktop. Com uso inteligente de `flexbox` e tamanhos relativos.

---

## 🎨 Estilo Visual

- Cores suaves e agradáveis aos olhos (gradientes azuis, verde escuro)
- Estilo **clean**, com bordas arredondadas e sombras suaves
- Tipografia com contraste entre elegante (Cinzel) e moderna (Montserrat)
- Feedbacks visuais para interações (hover, foco, alertas)

---

## 🧪 Melhorias Futuras

- [ ] Botão de volume e escolha de som personalizado
- [ ] Modo escuro
- [ ] Refatoração com Vue CLI (componentização real)
- [ ] Notificações push em segundo plano

---

## 🙋‍♀️ Autora

**Camila Peretto** – Desenvolvedora de Software

> Em um mundo cheio de distrações, gerenciar bem o tempo é o verdadeiro superpoder.  
> Esse projeto não é só um app, é um **manifesto de organização, foco e carinho pelo código**.
