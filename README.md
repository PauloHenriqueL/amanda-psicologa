# Site - Amanda Neuro Psicóloga

Site elegante e profissional para Amanda, Neuro Psicóloga em Belo Horizonte.

**Design inspirado em:** Psiangelo - Estilo minimalista e sofisticado com fundo preto e dourado.

## 🎨 Características

- ✨ Design elegante e minimalista (preto + dourado)
- 📱 Totalmente responsivo (mobile, tablet, desktop)
- ⚡ Animações suaves ao scroll
- 🎯 Layout profissional com 2 colunas
- 🔗 Links diretos para WhatsApp
- 📍 Seções bem organizadas
- 🚀 Otimizado para GitHub Pages

## 📝 Como Preencher as Informações

Abra o arquivo `index.html` e substitua todos os `{colocar x}` pelos dados reais:

### 1. **Frase Motivacional (Hero)**
Procure por: `{colocar frase motivacional}`

Exemplo:
```html
<p class="hero-quote">Uma escuta junguiana para a vida que se vive agora.</p>
```

### 2. **Descrição Inicial**
Procure por: `{colocar descrição breve - quem é Amanda e o que oferece}`

Exemplo:
```html
<div class="hero-description">
    <p>A casa de Amanda: clínica junguiana online em todo o Brasil, e um trabalho público 
    de estudo e escrita sobre a obra de Jung. Aqui você encontra a porta de entrada para tudo isso.</p>
</div>
```

### 3. **Seção Sobre**
Procure pelos 3 `{colocar...}` em:
```html
<div class="about-content">
    <p>{colocar biografia...}</p>
    <p>{colocar mais detalhes...}</p>
    <p>{colocar informações sobre...}</p>
</div>
```

Exemplo:
```html
<p>Sou psicóloga clínica com especialização em Psicologia Analítica, formada pela UFMG 
em 2015. Trabalho com abordagem junguiana, focando no autoconhecimento e no desenvolvimento pessoal.</p>

<p>Minha prática inclui avaliação neuropsicológica, psicoterapia individual e atendimento 
online através de plataformas seguras. Atendo tanto em consultório presencial quanto remotamente.</p>

<p>Acredito que a terapia é um espaço de escuta profunda, onde cada pessoa pode explorar 
seus processos internos e encontrar suas próprias respostas.</p>
```

### 4. **Serviços**
Procure pelos 4 cards de serviço e substitua:
- `{colocar serviço 1}` e `{colocar descrição}`

Exemplo:
```html
<div class="service-card">
    <h3>Psicoterapia Analítica</h3>
    <p>Atendimento individual focado na exploração do inconsciente, sonhos e padrões de comportamento.</p>
</div>

<div class="service-card">
    <h3>Avaliação Neuropsicológica</h3>
    <p>Avaliação completa para diagnóstico de déficits cognitivos, memória e atenção.</p>
</div>

<div class="service-card">
    <h3>Atendimento Online</h3>
    <p>Consultas via Zoom ou Google Meet com total privacidade e segurança.</p>
</div>

<div class="service-card">
    <h3>Supervisão Clínica</h3>
    <p>Supervisão para psicólogos e terapeutas que desejam aprofundar sua prática.</p>
</div>
```

### 5. **Localização**
Substitua as informações de atendimento:

```html
<div class="location-card">
    <h3>ATENDIMENTO ONLINE</h3>
    <p><strong>Plataforma:</strong> Zoom e Google Meet</p>
    <p><strong>Disponível em:</strong> Belo Horizonte e região</p>
    <p>Consultórios online com total privacidade. Agenda flexível.</p>
</div>

<div class="location-card">
    <h3>ATENDIMENTO PRESENCIAL</h3>
    <p><strong>Endereço:</strong> Av. Brasil, 1500 - Sala 302</p>
    <p><strong>Bairro:</strong> Lourdes, Belo Horizonte - MG</p>
    <p><strong>Estacionamento:</strong> Disponível no prédio</p>
</div>
```

### 6. **Contato - WhatsApp** ⭐ IMPORTANTE

Substitua `{colocar_numero}` com o número do WhatsApp **SEM símbolos**:

**Formato correto:** `5531999999999`
- `55` = país (Brasil)
- `31` = área (Belo Horizonte)
- `999999999` = seu número

```html
<a href="https://wa.me/5531999999999" class="contact-card whatsapp" target="_blank">
    <h3>WhatsApp</h3>
    <p>Envie uma mensagem</p>
    <span class="arrow">→</span>
</a>
```

### 7. **Contato - Email e Telefone**

```html
<div class="contact-card email">
    <h3>Email</h3>
    <p>amanda@example.com</p>
</div>

<div class="contact-card phone">
    <h3>Telefone</h3>
    <p>(31) 9 9999-9999</p>
</div>
```

### 8. **Footer - CREFONO**

```html
<p class="registration">Responsável Técnico: CREFONO/MG 12345</p>
```

## 🖼️ Adicionar Foto

1. **Prepare sua foto:**
   - Formato: JPEG ou PNG
   - Tamanho: 400x600px ou maior (proporção 2:3)
   - Nome: `amanda.jpg`

2. **Coloque na pasta:** `/img/amanda.jpg`

3. **Verifique o HTML:**
   ```html
   <img src="img/amanda.jpg" alt="Amanda - Neuro Psicóloga" class="profile-image">
   ```

## 🚀 Como Rodar Localmente

### Opção 1: Python (Recomendado)
```bash
cd /home/paulo/Documentos/projetos/amanda/page_amanda
python3 -m http.server 8000
```
Abra: **http://localhost:8000**

### Opção 2: Live Server (VSCode)
1. Instale a extensão "Live Server"
2. Clique com botão direito em `index.html`
3. Selecione "Open with Live Server"
4. Abrirá automaticamente

### Opção 3: Node.js
```bash
npm install -g http-server
cd /home/paulo/Documentos/projetos/amanda/page_amanda
http-server
```
Abra: **http://localhost:8080**

## 📂 Estrutura de Arquivos

```
page_amanda/
├── index.html        (Página principal)
├── styles.css        (Estilos)
├── script.js         (Animações)
├── README.md         (Este arquivo)
└── img/
    └── amanda.jpg    (Sua foto)
```

## 🎯 Checklist antes de publicar

- [ ] Preencher todos os `{colocar x}` no index.html
- [ ] Adicionar foto em `/img/amanda.jpg`
- [ ] Adicionar número do WhatsApp (formato: 5531999999999)
- [ ] Adicionar email e telefone
- [ ] Adicionar CREFONO
- [ ] Testar localmente com `python3 -m http.server 8000`
- [ ] Verificar links (especialmente WhatsApp)
- [ ] Verificar responsividade (mobile/tablet)

## 🌍 Hospedar no GitHub Pages

### 1. Inicializar Git
```bash
cd /home/paulo/Documentos/projetos/amanda/page_amanda
git init
git add .
git commit -m "Initial commit: site Amanda Neuro Psicóloga"
```

### 2. Criar repositório no GitHub
- Acesse https://github.com/new
- Nome: `amanda-psicologa` (ou outro)
- Deixe público

### 3. Fazer push
```bash
git remote add origin https://github.com/seu-usuario/amanda-psicologa.git
git branch -M main
git push -u origin main
```

### 4. Ativar GitHub Pages
1. Vá em **Settings > Pages**
2. Em "Source", selecione **main branch**
3. Clique em **Save**
4. Seu site estará em: `https://seu-usuario.github.io/amanda-psicologa`

## 🎨 Personalizar Cores

Para mudar de dourado para outra cor, edite `styles.css`:

```css
:root {
    --primary: #D4AF37;        /* Dourado - mude aqui */
    --primary-light: #E8C547;  /* Dourado claro - mude aqui */
    /* ... resto das cores */
}
```

**Outras cores sugeridas:**
- Verde: `#2ECC71`
- Azul: `#3498DB`
- Rosa: `#E891B8`
- Roxo: `#9B59B6`

## 📞 Suporte

- Dúvidas sobre GitHub Pages? Veja a [documentação oficial](https://docs.github.com/en/pages)
- Problemas com o site? Verifique o console do navegador (F12)

---

**Sucesso! Seu site está pronto para Amanda! 🎉**
