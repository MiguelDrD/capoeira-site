# 🥋 Site Navio Negreiro - Projeto Social de Capoeira

![Página Inicial](./assets/img/capa%20do%20site.png)

## 🎯 Sobre o Projeto

O **Projeto Social Movimento Navio Negreiro** é uma iniciativa dedicada à preservação da cultura afro-brasileira através da capoeira. Este website foi desenvolvido para modernizar a presença digital do grupo, oferecendo uma plataforma completa que reflete a energia, tradição e impacto social da capoeira.

### 💡 Motivação

O projeto surgiu da necessidade de:
- **Digitalizar a presença** do grupo de capoeira na internet
- **Preservar e divulgar** a cultura afro-brasileira
- **Facilitar o contato** entre a comunidade e o projeto
- **Modernizar a comunicação** com design responsivo e funcional
- **Aumentar o alcance** das atividades sociais do grupo

## 🚀 Funcionalidades Principais

### 🎨 **Design e Interface**
- **Layout Responsivo**: Adaptável para desktop, tablet e mobile
- **Paleta de Cores Consistente**: Branco, azul claro e preto (Cores temas do movimento)
- **Tipografia Moderna**: Combinação Roboto + Oswald para legibilidade
- **Animações Suaves**: Transições CSS3 para melhor experiência

### 🌙 **Tema Escuro/Claro**
```javascript
const themeToggle = document.getElementById(\'theme-toggle\');
themeToggle.addEventListener(\'click\', () => {
    document.body.dataset.theme = 
        document.body.dataset.theme === \'dark\' ? \'light\' : \'dark\';
    localStorage.setItem(\'theme\', document.body.dataset.theme);
});
```

### 📱 **Menu Mobile Responsivo**
- Menu hamburger animado para dispositivos móveis
- Navegação suave entre seções
- Fechamento automático ao selecionar item

### 📋 **Formulários Interativos**
- **Formulário de Voluntariado**: Inscrição para novos voluntários
- **Formulário de Contato**: Comunicação direta com o projeto
- **Validação em Tempo Real**: Feedback imediato para o usuário

### 🔝 **Navegação Aprimorada**
- Botão "Voltar ao Topo" com aparição suave
- Scroll suave entre seções
- Menu fixo com indicação da página atual

## 📄 Estrutura do Site

### 🏠 **Página Inicial (index.html)**
- Hero section com apresentação impactante
- Pilares do projeto (Inclusão, Educação, Transformação)
- Galeria visual da capoeira
- Call-to-action para engajamento

### 📖 **Sobre o Projeto (nossoprojeto.html)**
- História e origem do projeto
- Missão, visão e valores
- Estatísticas de impacto social
- Programas oferecidos (Infantil, Juvenil, Adulto)

### 🎯 **Nosso Propósito (proposito.html)**
- Objetivos e metas do projeto
- Impacto na comunidade
- Filosofia da capoeira aplicada

### 🎪 **Eventos (eventos.html)**
- Agenda de próximos eventos
- Tipos de atividades (Rodas, Workshops, Batizados)
- Galeria de eventos passados
- Instruções para participação

### 🏢 **Sedes (sedes.html)**
- Localização da sede principal
- Outras unidades e pontos de atendimento
- Infraestrutura disponível
- Informações de acesso e transporte

### 👨‍🏫 **Instrutores (instrutores.html)**
- Perfil do Mestre Deyva (fundador)
- Equipe de professores e instrutores
- Sistema de graduação da capoeira
- Oportunidades para novos instrutores

### 💝 **Contribua (contribua.html)**
- Formas de apoiar o projeto
- Doações financeiras e materiais
- Programa de voluntariado
- Formulários de inscrição

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com Flexbox e Grid
- **JavaScript**: Funcionalidades interativas vanilla
- **Font Awesome**: Biblioteca de ícones profissionais
- **Google Fonts**: Tipografia web otimizada

### Recursos Técnicos
```css
/* Exemplo de CSS responsivo */
@media (max-width: 768px) {
    .nav-list {
        flex-direction: column;
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        background: var(--background-color);
        transform: translateY(-100%);
        opacity: 0;
        transition: all 0.3s ease;
    }
}
```

### Performance
- **Otimização de Imagens**: Formatos WebP e compressão
- **CSS Minificado**: Redução do tamanho dos arquivos
- **JavaScript Modular**: Código organizado e eficiente
- **Carregamento Progressivo**: Melhoria na velocidade

## 📊 Resultados e Impacto

### Melhorias Implementadas
- ✅ **100% Responsivo**: Funciona perfeitamente em todos os dispositivos
- ✅ **Acessibilidade**: Navegação por teclado e leitores de tela
- ✅ **SEO Otimizado**: Meta tags e estrutura semântica
- ✅ **Performance**: Carregamento rápido e eficiente

### Métricas de Qualidade
- **Lighthouse Score**: 95+ em Performance, Acessibilidade e SEO
- **Cross-browser**: Compatível com Chrome, Firefox, Safari, Edge
- **Mobile-first**: Design pensado primeiro para dispositivos móveis

## 🔮 Próximos Passos

- [ ] Integração com sistema de pagamento para doações
- [ ] Blog para notícias e artigos sobre capoeira
- [ ] Sistema de inscrição online para aulas
- [ ] Galeria de vídeos das apresentações
- [ ] Área restrita para alunos

## 📞 Contato

**Projeto Social Navio Negreiro**
- 📧 Email: migueldrd18@gmail.com
- 📍 Localização: Riacho Fundo II, Brasília - DF
- 🌐 Website: [Em desenvolvimento]

---

**Desenvolvido com empenho para preservar a cultura da capoeira e promover transformação social**


![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  

![Responsive](https://img.shields.io/badge/Responsive-Design-blue)
![Capoeira](https://img.shields.io/badge/Capoeira-Cultura%20Brasileira-green)


