# 🌸 Episódio Emocional

> Uma jornada interativa de autoexploração emocional — reflexiva, acolhedora e minimalista.

**[▶ Ver ao vivo →](https://SEU-USUARIO.github.io/episodio-emocional)**

---

## 📖 Sobre o projeto

**Episódio Emocional** é uma aplicação web de página única (SPA) que guia o usuário por uma jornada estruturada de reflexão emocional, inspirada no modelo de **linha do tempo de episódios emocionais** da educação emocional.

A experiência foi projetada para ser semelhante a um app de journaling ou bem-estar mental — sem formulários tradicionais, mas sim como um processo de autoconhecimento guiado passo a passo.

---

## ✨ Funcionalidades

- **6 etapas progressivas** reveladas suavemente conforme o usuário avança
- **Navegação com Voltar/Continuar** — sem perder o que já foi preenchido
- **Seleção de emoções em dois níveis** — emoção primária + nuances específicas
- **Slider de intensidade** emocional (0 a 10)
- **Classificação da ação** — construtiva ou destrutiva
- **Perguntas de reestruturação cognitiva** geradas dinamicamente
- **Fluxograma automático** ao final, visualizando o episódio emocional completo
- **Resumo da jornada** com todas as respostas organizadas
- Design responsivo, animações suaves, sem dependências externas

---

## 🗺️ Estrutura das Etapas

| Etapa | Conteúdo |
|-------|----------|
| 1 · Situação | Condição anterior + Evento (limite 200 caracteres) |
| 2 · Emoções | Emoção primária → ramificações + Intensidade (0–10) |
| 3 · Pensamentos & Corpo | Pensamento automático + Mudanças físicas |
| 4 · Ações | Descrição da reação + Tipo (construtiva/destrutiva) |
| 5 · Reestruturação | Perguntas reflexivas + Condição posterior |
| 6 · Insight | Aprendizado final |
| ✦ Conclusão | Resumo + Fluxograma do episódio emocional |

---

## 🚀 Como publicar no GitHub Pages

### 1. Criar o repositório

```bash
# No terminal, dentro da pasta do projeto
git init
git add .
git commit -m "feat: episodio emocional v1"
```

### 2. Criar repositório no GitHub

1. Acesse [github.com/new](https://github.com/new)
2. Nome sugerido: `episodio-emocional`
3. Deixe **público**
4. **Não** inicialize com README (você já tem um)

### 3. Conectar e publicar

```bash
git remote add origin https://github.com/SEU-USUARIO/episodio-emocional.git
git branch -M main
git push -u origin main
```

### 4. Ativar GitHub Pages

1. No repositório → **Settings** → **Pages**
2. Em *Source*, selecione **Deploy from a branch**
3. Branch: `main` · Pasta: `/ (root)`
4. Clique em **Save**

Após ~2 minutos, o site estará disponível em:
```
https://SEU-USUARIO.github.io/episodio-emocional
```

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura da aplicação |
| CSS3 | Animações, layout, design system com variáveis |
| JavaScript (Vanilla) | Lógica de navegação, estados, geração do fluxograma |
| Google Fonts | Fraunces (serif) + DM Sans (sans-serif) |

> **Zero dependências externas.** Nenhum framework, nenhuma biblioteca JS, nenhum bundler necessário.

---

## 📁 Estrutura do repositório

```
episodio-emocional/
├── index.html      # Aplicação completa (HTML + CSS + JS em um único arquivo)
└── README.md       # Este arquivo
```

---

## 🎨 Design System

| Elemento | Valor |
|----------|-------|
| Fundo | `#FAF6EF` (creme suave) |
| Texto principal | `#3A3530` (quase preto) |
| Rosa | `#F0B8B0` / `#D4897E` |
| Amarelo | `#F5E4A0` / `#C9A82C` |
| Roxo | `#C8BCED` / `#7A65BB` |
| Azul | `#B8D4E8` / `#5A8FAA` |
| Laranja | `#F5C8A0` / `#C07840` |
| Tipografia principal | Fraunces (serif, itálico) |
| Tipografia corpo | DM Sans (400, 300) |

---

## 📚 Referências conceituais

O modelo de **linha do tempo de um episódio emocional** é baseado nos estudos de Paul Ekman sobre emoções e foi adaptado para fins educacionais pelo programa **LaLa — Educação Emocional**.

As etapas seguem a estrutura:
> **Condição Anterior → Evento → Gatilho → Estado Emocional → Ações → Condição Posterior**

Com o conceito de **Período Refratário de Filtragem Seletiva** — o momento em que a percepção se torna estreita e distorcida durante a emoção predominante.

---

## 📄 Licença

MIT — sinta-se livre para usar, adaptar e compartilhar.

---

<div align="center">
  Feito com 🌸 para quem quer se conhecer melhor
</div>
