# TikTok Downloader Pro - Versão Estática

Um site profissional e cinematográfico para baixar vídeos do TikTok sem marca d'água em alta qualidade.

## 📋 Características

- ✅ **Sem marca d'água** - Baixe vídeos em qualidade original
- ✅ **Alta qualidade (HD)** - Suporte para resolução 1920x1080
- ✅ **Múltiplas opções** - Escolha entre várias qualidades e formatos
- ✅ **Rápido e seguro** - Processamento instantâneo
- ✅ **Sem registro** - Nenhuma conta necessária
- ✅ **Design cinematográfico** - Interface elegante e moderna
- ✅ **Responsivo** - Funciona em mobile e desktop
- ✅ **Estático** - Sem dependências de servidor

## 🚀 Como Usar

### Opção 1: Hospedagem Local
1. Abra o arquivo `index.html` diretamente no navegador
2. Cole o link do vídeo do TikTok
3. Clique em "Buscar"
4. Escolha a qualidade desejada
5. Clique em "Baixar" para fazer o download

### Opção 2: Hospedagem em Servidor Web
1. Faça upload do arquivo `index.html` para seu servidor web
2. Acesse via URL do seu domínio
3. Use normalmente

### Opção 3: Hospedagem em Plataformas Estáticas

#### GitHub Pages
```bash
# 1. Crie um repositório no GitHub
# 2. Faça upload do arquivo index.html
# 3. Vá para Settings > Pages
# 4. Selecione "Deploy from a branch"
# 5. Escolha "main" como branch
# 6. Seu site estará disponível em: https://seu-usuario.github.io/seu-repositorio
```

#### Netlify
```bash
# 1. Acesse https://netlify.com
# 2. Clique em "New site from Git" ou "Deploy manually"
# 3. Faça upload do arquivo index.html
# 4. Seu site estará online em minutos
```

#### Vercel
```bash
# 1. Acesse https://vercel.com
# 2. Clique em "New Project"
# 3. Selecione "Other" e faça upload dos arquivos
# 4. Seu site estará disponível em um domínio Vercel
```

#### Cloudflare Pages
```bash
# 1. Acesse https://pages.cloudflare.com
# 2. Clique em "Create a project"
# 3. Faça upload do arquivo index.html
# 4. Seu site estará online
```

## 📱 Formatos Suportados

### Vídeos
- **HD (1920x1080)** - Melhor qualidade disponível
- **Qualidade Padrão** - Qualidade média
- **Com Marca d'água** - Fallback se outras não estiverem disponíveis

### Áudio
- **Música Original** - Áudio do vídeo
- **Download de Áudio** - Versão para download

## 🔧 Requisitos Técnicos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet
- Nenhuma instalação necessária
- Nenhuma dependência de servidor

## 📊 Como Funciona

1. **Validação**: O site valida se o link é um URL válido do TikTok
2. **Processamento**: Envia o link para a API TikWM
3. **Extração**: Extrai informações do vídeo (thumbnail, título, duração)
4. **Opções**: Oferece múltiplas opções de qualidade e formato
5. **Download**: Inicia o download direto para sua galeria

## 🛡️ Privacidade e Segurança

- Nenhum dado é armazenado no servidor
- Todos os processamentos são feitos em tempo real
- Nenhuma conta ou registro necessário
- Links são processados apenas quando você clica em "Buscar"
- Nenhum rastreamento de usuário

## 🌐 Domínios Personalizados

Se você registrou um domínio, pode apontá-lo para qualquer plataforma de hospedagem:

1. Acesse o painel de controle do seu registrador de domínio
2. Localize as configurações de DNS
3. Adicione os registros apontando para sua plataforma de hospedagem
4. Aguarde a propagação DNS (pode levar até 48 horas)

## 📧 Suporte

Para reportar problemas ou sugerir melhorias, entre em contato através do seu email.

## 📄 Licença

Este projeto é fornecido como está, para uso pessoal e comercial.

## 🎯 Monetização com Google AdSense

Para registrar este site no Google AdSense:

1. Hospede o site em um domínio próprio
2. Acesse https://www.google.com/adsense/
3. Clique em "Começar"
4. Insira a URL do seu site
5. Adicione o código de verificação do AdSense ao HTML
6. Aguarde aprovação (24h a alguns dias)

### Requisitos do Google AdSense:
- Site hospedado em domínio próprio
- Conteúdo original e útil
- Política de Privacidade (opcional, mas recomendado)
- Sem conteúdo proibido
- Tráfego mínimo recomendado

## 🚀 Próximas Melhorias

- [ ] Estatísticas de download em tempo real
- [ ] Compartilhamento em redes sociais
- [ ] Histórico de downloads (localStorage)
- [ ] Modo claro/escuro
- [ ] Suporte a múltiplos idiomas
- [ ] Integração com Google Analytics

---

**Versão**: 1.0.0  
**Última atualização**: Maio 2026  
**Desenvolvido com**: HTML5, CSS3, JavaScript Vanilla
