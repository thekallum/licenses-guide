<div align="center">
<img src="https://cdn-icons-png.flaticon.com/512/6090/6090957.png" width="300" alt="Software License Scroll">

# Guia de Licenças de Software

![Status](https://img.shields.io/badge/Status-Completo-success?logo=github&style=for-the-badge)
![Tópicos](https://img.shields.io/badge/Tópicos-GPL%2C%20MIT%2C%20Apache%2C%20BSD%20e%20mais-blue?style=for-the-badge)
![Linguagem](https://img.shields.io/badge/Linguagem-Português-informational?style=for-the-badge)

Um guia **completo e objetivo** sobre as principais licenças de software, detalhando suas **permissões, limitações** e consequências práticas para desenvolvedores e usuários.

[**Reportar um Erro/Sugestão**](https://github.com/thekallum/licenses-guide/issues)
</div>

---

## 📑 Índice

1. [Introdução](#-introdução)
2. [Tipos de Licenças](#-tipos-de-licenças)
3. [Licenças Permissivas](#-licenças-permissivas)
4. [Licenças Copyleft](#-licenças-copyleft)
5. [Licenças Proprietárias](#-licenças-proprietárias)
6. [Licenças Creative Commons](#-licenças-creative-commons)
7. [Outras Licenças Importantes](#-outras-licenças-importantes)
8. [Como Escolher uma Licença](#-como-escolher-uma-licença)
9. [Comparação Rápida](#-comparação-rápida)
10. [Perguntas Frequentes](#-perguntas-frequentes)

---

## 🎯 Introdução

Uma **licença de software** é um documento jurídico que estabelece as regras de uso, modificação e distribuição de um programa. A escolha adequada da licença é essencial para proteger seus direitos autorais e definir claramente como terceiros podem interagir com seu código.

### Por que as licenças são fundamentais?

- **Proteção Jurídica:** Estabelece e resguarda seus direitos como autor
- **Transparência:** Define explicitamente o que usuários podem ou não fazer
- **Colaboração:** Facilita e incentiva contribuições de terceiros
- **Uso Comercial:** Determina se e como o software pode ser explorado comercialmente

---

## 📊 Tipos de Licenças

As licenças de software dividem-se em três categorias fundamentais:

### 1. **Licenças Permissivas (Permissive)**
- Autorizam uso, modificação e redistribuição com restrições mínimas
- Não obrigam trabalhos derivados a adotarem a mesma licença
- Exemplos: MIT, BSD, Apache 2.0

### 2. **Licenças Copyleft**
- Exigem que trabalhos derivados mantenham a mesma licença original
- Asseguram que o software permaneça livre e aberto
- Exemplos: GPL, AGPL, MPL

### 3. **Licenças Proprietárias**
- Código fechado com restrições rigorosas de uso
- Geralmente exigem pagamento ou acordos comerciais
- Exemplos: Microsoft EULA, Oracle License

</details>

---

## ✅ Licenças Permissivas

<details>
<summary><b>MIT License</b></summary>

**📌 Características:**
- Uma das licenças mais populares e diretas do ecossistema open source
- Permite uso comercial irrestrito e modificações livres
- Exige apenas atribuição ao autor original
- Amplamente adotada em projetos de código aberto

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**❌ Limitações:**
- Não oferece garantias
- Isenta o autor de responsabilidade

**📝 Exemplo de uso:**
```
Copyright (c) 2025 Seu Nome

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

**🔥 Projetos notáveis:** React, Node.js, jQuery, Rails

</details>

<details>
<summary><b>BSD License (2-Clause e 3-Clause)</b></summary>

**📌 Características:**
- Semelhante à MIT, com variações específicas
- BSD 2-Clause (Simplificada): Praticamente equivalente à MIT
- BSD 3-Clause: Inclui cláusula sobre uso do nome do projeto

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**❌ Restrições:**
- Proíbe usar nomes dos contribuidores para endossar produtos derivados (3-Clause)

**🔥 Projetos notáveis:** FreeBSD, Django, Flask

</details>

<details>
<summary><b>Apache License 2.0</b></summary>

**📌 Características:**
- Mais abrangente e detalhada que MIT e BSD
- Inclui concessão explícita de direitos sobre patentes
- Exige documentação de alterações significativas

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes
- ✓ Uso privado

**❌ Restrições:**
- Deve incluir arquivo NOTICE quando existente
- Obriga declaração de mudanças significativas
- Proteção de marcas registradas

**🔥 Projetos notáveis:** Android, Apache HTTP Server, Kubernetes, Swift

</details>

<details>
<summary><b>ISC License</b></summary>

**📌 Características:**
- Funcionalmente idêntica à MIT e BSD 2-Clause
- Linguagem mais moderna e concisa
- Preferida por alguns desenvolvedores devido à sua simplicidade

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**🔥 Projetos notáveis:** npm, OpenBSD

</details>

---

## 🔄 Licenças Copyleft

<details>
<summary><b>GNU General Public License (GPL v3)</b></summary>

**📌 Características:**
- Licença copyleft rigorosa
- Qualquer trabalho derivado DEVE adotar a GPL
- Protege contra "tivoização" (hardware que bloqueia modificações)
- Inclui proteção explícita contra patentes

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes

**❌ Restrições:**
- ✗ Trabalhos derivados devem ser licenciados sob GPL
- ✗ Código-fonte deve ser disponibilizado obrigatoriamente
- ✗ Mudanças devem ser documentadas
- ✗ Proibido adicionar restrições adicionais

**🔥 Projetos notáveis:** Linux Kernel, Git, GIMP, WordPress

</details>

<details>
<summary><b>GNU General Public License (GPL v2)</b></summary>

**📌 Características:**
- Versão anterior da GPL
- Menos restritiva em determinados aspectos
- Ainda amplamente utilizada em projetos consolidados

**Diferenças principais da v3:**
- Não possui proteção contra tivoização
- Termos sobre patentes menos explícitos
- Compatibilidade diferenciada com outras licenças

**🔥 Projetos notáveis:** Linux Kernel (especificamente v2)

</details>

<details>
<summary><b>GNU Lesser General Public License (LGPL)</b></summary>

**📌 Características:**
- Copyleft "moderado" ou "parcial"
- Permite vinculação (linking) com código proprietário
- Especialmente comum em bibliotecas

**✅ Permite:**
- ✓ Uso comercial
- ✓ Vinculação com código proprietário
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- ✗ Modificações na biblioteca devem permanecer LGPL
- ✗ Código-fonte da biblioteca modificada deve ser disponibilizado

**🔥 Projetos notáveis:** Qt, GTK+, LibreOffice

</details>

<details>
<summary><b>GNU Affero General Public License (AGPL)</b></summary>

**📌 Características:**
- Versão mais restritiva da GPL
- Fecha a "brecha de rede/SaaS"
- Obriga disponibilização do código mesmo em uso via rede

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- ✗ Código-fonte deve ser disponibilizado mesmo para usuários remotos (via rede)
- ✗ Trabalhos derivados devem ser AGPL
- ✗ Altamente restritiva para uso comercial tradicional

**🔥 Projetos notáveis:** MongoDB (anteriormente), Mastodon, NextCloud

</details>

<details>
<summary><b>Mozilla Public License (MPL) 2.0</b></summary>

**📌 Características:**
- Copyleft "moderado" aplicado no nível de arquivo
- Permite combinação com código proprietário
- Mais flexível que GPL

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Combinação com código proprietário
- ✓ Distribuição

**❌ Restrições:**
- ✗ Arquivos MPL modificados devem permanecer sob MPL
- ✗ Código-fonte dos arquivos MPL deve ser disponibilizado

**🔥 Projetos notáveis:** Firefox, Thunderbird, LibreOffice

</details>

<details>
<summary><b>Eclipse Public License (EPL)</b></summary>

**📌 Características:**
- Similar à MPL
- Copyleft moderado
- Particularmente popular em projetos Java

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes

**🔥 Projetos notáveis:** Eclipse IDE, OpenJ9

</details>

---

## 🔒 Licenças Proprietárias

<details>
<summary><b>End-User License Agreement (EULA)</b></summary>

**📌 Características:**
- Acordo de licença para usuário final
- Código-fonte fechado
- Uso rigidamente limitado aos termos contratuais

**✅ Geralmente permite:**
- Instalação em número limitado de dispositivos
- Uso pessoal ou comercial (conforme versão adquirida)

**❌ Restrições:**
- ✗ Sem acesso ao código-fonte
- ✗ Sem direito de modificação
- ✗ Sem autorização para redistribuição
- ✗ Geralmente exige pagamento ou licenciamento

**Exemplos:** Microsoft Office, Adobe Photoshop, AutoCAD

</details>

<details>
<summary><b>Freeware</b></summary>

**📌 Características:**
- Gratuito para uso, porém código fechado
- Não é software de código aberto
- Sem autorização para modificação

**Exemplos:** WinRAR (trial perpétuo), Skype, Spotify Free

</details>

<details>
<summary><b>Shareware</b></summary>

**📌 Características:**
- Período de teste gratuito por tempo limitado
- Exige aquisição para uso contínuo
- Código-fonte fechado

**Exemplos:** WinZip, diversos jogos independentes

</details>

---

## 🎨 Licenças Creative Commons

<details>
<summary><b>CC0 (Public Domain)</b></summary>

**📌 Características:**
- Dedicação ao domínio público
- Sem restrições de uso
- Autor renuncia a todos os direitos

**✅ Permite:** QUALQUER USO

</details>

<details>
<summary><b>CC BY (Attribution)</b></summary>

**📌 Características:**
- Exige atribuição ao autor original
- Altamente permissiva

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- Obrigatório dar crédito ao autor

</details>

<details>
<summary><b>CC BY-SA (Attribution-ShareAlike)</b></summary>

**📌 Características:**
- Exige atribuição ao autor
- Copyleft - trabalhos derivados devem usar a mesma licença

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- Obrigatório dar crédito ao autor
- Derivados devem ser licenciados sob CC BY-SA

**🔥 Usado por:** Wikipedia, Wikimedia

</details>

<details>
<summary><b>CC BY-NC (Attribution-NonCommercial)</b></summary>

**📌 Características:**
- Exige atribuição ao autor
- Proíbe exploração comercial

**❌ Restrições:**
- ✗ Vedado uso comercial

</details>

<details>
<summary><b>CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)</b></summary>

**📌 Características:**
- Exige atribuição ao autor
- Proíbe uso comercial
- Copyleft

**❌ Restrições:**
- ✗ Vedado uso comercial
- ✗ Derivados devem ser licenciados sob CC BY-NC-SA

</details>

<details>
<summary><b>CC BY-ND (Attribution-NoDerivatives)</b></summary>

**📌 Características:**
- Exige atribuição ao autor
- Proíbe criação de obras derivadas

**❌ Restrições:**
- ✗ Vedadas modificações

</details>

<details>
<summary><b>CC BY-NC-ND (Attribution-NonCommercial-NoDerivatives)</b></summary>

**📌 Características:**
- Mais restritiva das licenças Creative Commons
- Apenas compartilhamento sem alterações
- Vedado uso comercial

**❌ Restrições:**
- ✗ Vedado uso comercial
- ✗ Vedadas modificações

</details>

---

## 🔧 Outras Licenças Importantes

<details>
<summary><b>Unlicense</b></summary>

**📌 Características:**
- Dedicação ao domínio público
- Ausência total de restrições
- Filosofia "anti-licença"

**✅ Permite:** QUALQUER USO

</details>

<details>
<summary><b>WTFPL (Do What The F*** You Want To Public License)</b></summary>

**📌 Características:**
- Licença humorística porém juridicamente válida
- Extremamente permissiva
- Ausência total de restrições

**✅ Permite:** LITERALMENTE QUALQUER COISA

</details>

<details>
<summary><b>Boost Software License</b></summary>

**📌 Características:**
- Semelhante à MIT
- Amplamente utilizada em bibliotecas C++
- Extremamente simples e direta

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

</details>

<details>
<summary><b>Artistic License 2.0</b></summary>

**📌 Características:**
- Popular na comunidade Perl
- Oferece flexibilidade quanto a modificações

</details>

<details>
<summary><b>Zlib License</b></summary>

**📌 Características:**
- Altamente permissiva
- Semelhante à MIT
- Popular em bibliotecas gráficas e de compressão

**🔥 Projetos notáveis:** zlib, libpng

</details>

<details>
<summary><b>PostgreSQL License</b></summary>

**📌 Características:**
- Semelhante à MIT/BSD
- Altamente permissiva

**🔥 Projetos notáveis:** PostgreSQL

</details>

---

## 🎯 Como Escolher uma Licença

<details>
<summary><b>📊 Fluxograma de Decisão</b></summary>
    
```
┌─────────────────────────────────────────────────────────────┐
│ COMEÇO: O que você está licenciando?                        │
└─────────────────────────────────────────────────────────────┘
                          │
                          ▼
              ┌───────────────────────┐
              │  CÓDIGO ou CONTEÚDO?  │
              └───────────────────────┘
                     │           │
        ┌────────────┘           └────────────┐
        │                                     │
        ▼                                     ▼
   ┌─────────┐                          ┌──────────┐
   │ CÓDIGO  │                          │ CONTEÚDO │
   └─────────┘                          │(docs/art)│
        │                               └──────────┘
        ▼                                     │
┌──────────────────────┐                      ▼
│ Permitir uso         │              ┌──────────────────┐
│ comercial?           │              │ Permitir uso     │
└──────────────────────┘              │ comercial?       │
     │          │                     └──────────────────┘
     │          │                          │          │
    NÃO        SIM                        NÃO        SIM
     │          │                          │          │
     ▼          ▼                          ▼          ▼
┌────────┐  ┌──────────────┐      ┌────────────┐  ┌─────────────┐
│CC BY-NC│  │ Será usado   │      │ Permitir   │  │ Permitir    │
│   -SA  │  │ via rede?    │      │modificar?  │  │ modificar?  │
└────────┘  └──────────────┘      └─────────────┘ └─────────────┘
                 │      │             │      │        │      │
                NÃO    SIM           NÃO    SIM      NÃO    SIM
                 │      │             │      │        │      │
                 │      ▼             ▼      ▼        ▼      ▼
                 │  ┌────────┐   ┌────────┐ ┌────┐ ┌────┐ ┌────────┐
                 │  │ AGPL   │   │CC BY-NC│ │CC  │ │CC  │ │Manter  │
                 │  │  v3    │   │  -ND   │ │BY  │ │BY  │ │licença?│
                 │  └────────┘   └────────┘ │-ND │ └────┘ └────────┘
                 │                          └────┘           │     │
                 ▼                                          SIM   NÃO
         ┌───────────────┐                                   │     │
         │ Derivados     │                                   ▼     │
         │ devem ser     │                              ┌────────┐ │
         │ open source?  │                              │CC BY-SA│ │
         └───────────────┘                              └────────┘ │
              │        │                                           │
             NÃO      SIM                                          │
              │        │                                           │
              ▼        ▼                                           │
         ┌────────┐ ┌──────────────┐                               │
         │Patentes│ │ Nível de     │                               │
         │importantes? copyleft?   │                               │
         └────────┘ └──────────────┘                               │
            │    │     │    │    │                                 │
           NÃO  SIM  FORTE MÉDIO FRACO                             │
            │    │     │    │    │                                 │
            ▼    ▼     ▼    ▼    ▼                                 │
        ┌────┐┌────┐┌────┐┌────┐┌────┐                             │
        │MIT ││Apache GPL │MPL ││LGPL│                             │
        │BSD ││ 2.0 │ v3 ││2.0 ││    │                             │ 
        └────┘└────┘└────┘└────┘└────┘                             │
                                                                   │
        ┌──────────────────────────────────────────────────────────┘
        │
        ▼
┌──────────────────┐
│ Domínio Público? │
│ (Unlicense/CC0)  │
└──────────────────┘
```

**💡 Dicas rápidas:**
- **Para bibliotecas:** LGPL ou Apache 2.0 (facilita adoção)
- **Para aplicações web:** AGPL v3 (fecha brecha SaaS) ou MIT (liberdade total)
- **Para frameworks:** MIT ou Apache 2.0 (remove barreiras de adoção)
- **Para ferramentas CLI:** MIT, GPL v3 ou Apache 2.0
- **Para projetos educacionais:** MIT ou Unlicense (simplicidade)
- **Se tiver dúvida:** MIT (equilibra liberdade e proteção)

</details>

<details>
<summary><b>💡 Recomendações por Cenário de Uso</b></summary>

### 🚀 Projeto Open Source de Propósito Geral
**Recomendado:** MIT ou Apache 2.0
- **MIT:** Máxima simplicidade, ideal para projetos menores ou pessoais
- **Apache 2.0:** Melhor para projetos corporativos (proteção de patentes)
- Maximiza taxa de adoção entre desenvolvedores e empresas
- Permite exploração comercial sem restrições
- Não impõe obrigações complexas aos usuários

**Quando escolher MIT:** Projetos pequenos a médios, bibliotecas simples, ferramentas utilitárias
**Quando escolher Apache:** Projetos empresariais, código que pode envolver patentes, grandes frameworks

---

### 🛡️ Preservar a Liberdade do Software
**Recomendado:** GPL v3 (forte) ou MPL 2.0 (moderado)
- **GPL v3:** Garante que todo o ecossistema permaneça livre
- **MPL 2.0:** Copyleft apenas nos arquivos modificados (mais flexível)
- Impede apropriação proprietária do seu trabalho
- Cria ecossistema colaborativo obrigatório
- Protege contra uso em produtos fechados

**Use GPL v3 se:** Quer garantir liberdade total, trabalha em software de infraestrutura crítica
**Use MPL 2.0 se:** Quer equilíbrio entre liberdade e adoção comercial

---

### 📚 Biblioteca/Framework/SDK
**Recomendado:** Apache 2.0, MIT ou LGPL
- **Apache 2.0 ou MIT:** Máxima adoção, inclusive em projetos proprietários
- **LGPL:** Mantém a biblioteca livre, mas permite uso em software proprietário
- Facilita integração em projetos comerciais
- Reduz barreiras de entrada para empresas
- Aumenta base de usuários e contribuidores

**Escolha Apache/MIT se:** Prioriza adoção massiva
**Escolha LGPL se:** Quer que melhorias na biblioteca permaneçam livres

---

### 🌐 Aplicação Web/SaaS/API
**Recomendado:** AGPL v3 (proteção forte) ou MIT (liberdade total)
- **AGPL v3:** Obriga compartilhamento de código mesmo em uso via rede
- **MIT:** Se não se importa com uso em serviços fechados
- AGPL fecha a brecha de "software como serviço"
- Garante que modificações em serviços web sejam compartilhadas
- Importante se o modelo de negócio depende do código aberto

**Use AGPL v3 se:** Quer impedir que empresas usem seu código em SaaS fechado
**Use MIT se:** Quer máxima liberdade de uso, inclusive em serviços comerciais

---

### 🎮 Software de Entretenimento (Jogos, Apps)
**Recomendado:** MIT, BSD ou GPL v3
- **MIT/BSD:** Se quer permitir modificações comerciais (mods pagos, ports)
- **GPL v3:** Se quer que melhorias retornem à comunidade
- Facilita criação de mods e conteúdo pela comunidade
- Define claramente direitos sobre assets e código

**Considere também:** Dual licensing (GPL para comunidade + comercial para empresas)

---

### 📖 Documentação/Tutoriais/Livros
**Recomendado:** CC BY ou CC BY-SA
- **CC BY:** Máxima disseminação do conhecimento
- **CC BY-SA:** Estilo "copyleft" para documentação (como Wikipedia)
- Permite traduções e adaptações
- Facilita reutilização educacional
- Não é adequada para código (use licenças de software)

**Use CC BY se:** Quer máxima disseminação
**Use CC BY-SA se:** Quer que derivados também sejam livres

---

### 🎓 Projeto Educacional/Acadêmico
**Recomendado:** MIT, BSD ou Unlicense
- Máxima simplicidade para estudantes
- Fácil compreensão dos termos
- Não impõe obrigações complexas
- Permite uso em trabalhos acadêmicos posteriores

**Unlicense:** Para exemplos didáticos que podem ser copiados livremente
**MIT:** Para projetos que serão mantidos e têm valor

---

### 💼 Software Corporativo que será Open Source
**Recomendado:** Apache 2.0 ou MIT
- **Apache 2.0:** Preferida por empresas (proteção clara de patentes)
- Proteção legal mais robusta
- Termos sobre contribuições mais claros
- Compatível com ambiente corporativo

**Apache 2.0 é superior se:** Há risco de disputas de patentes, empresa tem portfólio IP

---

### 🔧 Ferramentas de Desenvolvimento/CLI
**Recomendado:** MIT ou GPL v3
- **MIT:** Se quer adoção massiva
- **GPL v3:** Se quer que melhorias sejam compartilhadas
- Ferramentas CLI geralmente não têm "linking" complexo
- Copyleft é mais claro nesse contexto

---

### 🔬 Pesquisa Científica/Algoritmos
**Recomendado:** BSD 3-Clause, MIT ou Apache 2.0
- Facilita reprodutibilidade científica
- Permite uso acadêmico e comercial
- BSD 3-Clause protege reputação dos autores

**Considere também:** Publicar algoritmos sob CC BY para citações acadêmicas

---

### 🎨 Conteúdo Criativo (não-código)
**Recomendado:** Licenças Creative Commons
- **CC0:** Domínio público total
- **CC BY:** Requer atribuição
- **CC BY-SA:** Copyleft criativo
- **CC BY-NC-SA:** Para conteúdo que não quer comercializado

**Nunca use GPL/MIT para:** Arte, música, textos, imagens (use CC)

---

### 🤝 Projeto Colaborativo Multi-Empresa
**Recomendado:** Apache 2.0 ou MPL 2.0
- Termos claros sobre contribuições
- Proteção de patentes explícita
- Reduz riscos legais entre parceiros

---

### ⚡ Decisões Rápidas por Tipo

| Tipo de Projeto | 1ª Opção | 2ª Opção | 3ª Opção |
|-----------------|----------|----------|----------|
| App Web | MIT | AGPL v3 | Apache 2.0 |
| Biblioteca | Apache 2.0 | MIT | LGPL |
| Framework | MIT | Apache 2.0 | BSD |
| API/Backend | AGPL v3 | MIT | GPL v3 |
| CLI Tool | MIT | GPL v3 | Apache 2.0 |
| Game Engine | MIT | GPL v3 | Apache 2.0 |
| Documentação | CC BY | CC BY-SA | - |
| Dataset/Dados | CC0 | CC BY | - |
| Algoritmo Científico | BSD | MIT | Apache 2.0 |

</details>

---

## 📊 Comparação Rápida

| Licença | Uso Comercial | Modificação | Distribuição | Copyleft | Patentes |
|---------|---------------|-------------|--------------|----------|----------|
| **MIT** | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| **Apache 2.0** | ✅ | ✅ | ✅ | ❌ | ✅ |
| **GPL v3** | ✅ | ✅ | ✅ | ✅ Rigoroso | ✅ |
| **LGPL** | ✅ | ✅ | ✅ | ⚠️ Moderado | ✅ |
| **AGPL v3** | ✅ | ✅ | ✅ | ✅ Muito Rigoroso | ✅ |
| **MPL 2.0** | ✅ | ✅ | ✅ | ⚠️ Moderado | ✅ |
| **BSD 3-Clause** | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| **CC BY** | ✅ | ✅ | ✅ | ❌ | ❌ |
| **CC BY-SA** | ✅ | ✅ | ✅ | ✅ | ❌ |
| **CC BY-NC** | ❌ | ✅ | ✅ | ❌ | ❌ |
| **Unlicense** | ✅ | ✅ | ✅ | ❌ | ❌ |

**Legenda:**
- ✅ Sim / Permitido / Protegido
- ❌ Não / Vedado / Sem proteção
- ⚠️ Parcial / Condicional

</details>

---

## ❓ Perguntas Frequentes (FAQ)

<details>
<summary><b>1. Posso alterar a licença do meu projeto posteriormente?</b></summary>

**Resposta curta:** Sim, mas com limitações importantes.

**Detalhes:**
- **Versões futuras:** Você pode licenciar novas versões sob licença diferente
- **Versões já distribuídas:** Continuam sob a licença original (você não pode "revogar" licenças já concedidas)
- **Múltiplos contribuidores:** É necessário obter consentimento de TODOS os contribuidores que detêm direitos autorais
- **Alternativa:** Algumas licenças permitem "ou versão posterior" (ex: "GPL v3 or later")

**Exemplo prático:** Se seu projeto está sob MIT e tem 50 contribuidores, você precisaria de permissão de todos os 50 para mudar para GPL v3.

**Solução:** Use um CLA (Contributor License Agreement) desde o início, permitindo que você altere licenças no futuro.

</details>

<details>
<summary><b>2. Posso aplicar múltiplas licenças simultaneamente (dual licensing)?</b></summary>

**Resposta curta:** Sim, e é uma estratégia comum de monetização.

**Como funciona:**
- Você oferece o software sob duas (ou mais) licenças
- Usuários escolhem qual licença seguir
- Comum: GPL (gratuita) + Licença Comercial (paga)

**Exemplos reais:**
- **MySQL:** GPL (open source) + Licença Comercial
- **Qt:** LGPL (open source) + Licença Comercial
- **MongoDB (antigamente):** AGPL + Licença Comercial

**Vantagens:**
- Mantém versão open source viva
- Permite monetização para uso proprietário
- Empresas pagam para evitar obrigações do copyleft

**Requisito:** Você deve deter 100% dos direitos autorais (ou ter CLAs assinados por contribuidores)

</details>

<details>
<summary><b>3. Quais licenças são incompatíveis com GPL?</b></summary>

**Incompatibilidades principais:**

**GPL v2 é incompatível com:**
- Apache 2.0 (cláusula de patentes conflita)
- Código proprietário
- BSD 4-Clause (cláusula de publicidade)

**GPL v3 é incompatível com:**
- GPL v2 (a menos que seja "v2 or later")
- Código proprietário
- Licenças com restrições adicionais não permitidas pela GPL

**Compatibilidades (podem ser combinadas COM GPL):**
- MIT → GPL ✅
- BSD 2-Clause → GPL ✅
- BSD 3-Clause → GPL ✅
- Apache 2.0 → GPL v3 ✅ (mas não v2)
- LGPL → GPL ✅

**Regra geral:** Licenças permissivas são compatíveis com GPL (você pode incorporar código MIT em projeto GPL). O inverso NÃO é verdade (você NÃO pode incorporar código GPL em projeto MIT).

</details>

<details>
<summary><b>4. Qual a diferença entre "permissive" e "copyleft"?</b></summary>

**Licenças Permissivas (MIT, BSD, Apache):**
- **Filosofia:** Máxima liberdade, mínimas restrições
- **Obrigações:** Apenas atribuição ao autor original
- **Derivados:** Podem ser proprietários/fechados
- **Analogia:** "Faça o que quiser, só me dê crédito"

**Licenças Copyleft (GPL, AGPL, MPL):**
- **Filosofia:** Garantir que o software permaneça livre
- **Obrigações:** Código-fonte deve continuar disponível
- **Derivados:** Devem usar a mesma licença (ou compatível)
- **Analogia:** "Você é livre para usar, mas mantenha a liberdade para outros"

**Níveis de Copyleft:**
- **Forte (GPL):** Todo o projeto derivado deve ser GPL
- **Moderado (MPL, LGPL):** Apenas partes modificadas devem manter licença
- **Fraco (LGPL):** Permite linking com código proprietário

**Qual escolher?**
- **Permissiva:** Se quer máxima adoção (empresas adoram)
- **Copyleft:** Se quer garantir que permanecerá open source

</details>

<details>
<summary><b>5. Meu projeto pessoal/hobby precisa de licença?</b></summary>

**Resposta:** SIM, absolutamente!

**Por quê?**
- **Sem licença = "Todos os direitos reservados"** (copyright padrão)
- Ninguém pode legalmente usar, copiar, modificar ou distribuir seu código
- Mesmo que esteja no GitHub público, não significa que é "livre"

**O que acontece sem licença:**
- ❌ Empresas não podem usar (risco legal)
- ❌ Desenvolvedores não podem contribuir (não sabem se podem)
- ❌ Não pode ser incluído em outras ferramentas
- ❌ Não é considerado "open source" de verdade

**Solução simples:**
1. Adicione um arquivo `LICENSE` na raiz do projeto
2. Copie o texto da licença escolhida (MIT é ótima para começar)
3. Substitua o ano e nome do autor
4. Mencione no README

**Exceção:** Se realmente não quer que ninguém use, não adicione licença (mas então por que tornar público?)

</details>

<details>
<summary><b>6. Posso utilizar código GPL em meu produto comercial?</b></summary>

**Resposta curta:** Sim, mas com obrigações rigorosas.

**O que a GPL permite:**
- ✅ Usar o código
- ✅ Modificar o código
- ✅ Vender o software (sim, GPL permite venda!)
- ✅ Uso comercial interno na empresa

**O que a GPL exige:**
- ❗ Seu produto completo deve ser licenciado sob GPL
- ❗ Você deve fornecer código-fonte completo aos usuários
- ❗ Não pode adicionar restrições adicionais (DRM, por exemplo)
- ❗ Mudanças devem ser documentadas

**Cenários comuns:**

**✅ PERMITIDO:**
- Vender software GPL (você pode cobrar pela distribuição)
- Usar GPL internamente na empresa (sem distribuir)
- Oferecer suporte pago para software GPL

**❌ NÃO PERMITIDO:**
- Incorporar biblioteca GPL em software proprietário
- Distribuir software GPL sem código-fonte
- Criar versão proprietária de software GPL

**Alternativas para produtos comerciais:**
- Use **LGPL** (permite linking com código proprietário)
- Use **MIT/Apache** (permitem uso proprietário)
- Negocie **dual licensing** com autor original
- Reimplemente funcionalidade sem usar código GPL

</details>

<details>
<summary><b>7. Como adicionar uma licença ao meu projeto corretamente?</b></summary>

**Passo a passo completo:**

**1. Escolha a licença**
- Use o fluxograma deste guia
- Visite [choosealicense.com](https://choosealicense.com)

**2. Crie arquivo LICENSE**
```bash
# Na raiz do projeto
touch LICENSE
# ou
touch LICENSE.md
```

**3. Copie o texto completo**
- Pegue o texto oficial da licença escolhida
- Substitua `[year]` pelo ano atual
- Substitua `[fullname]` por seu nome ou nome da organização

**4. Adicione cabeçalhos nos arquivos de código**

Exemplo para MIT:
```python
# Copyright (c) 2025 Seu Nome
# Licensed under the MIT License
# See LICENSE file in the project root
```

Exemplo para GPL:
```python
# Copyright (C) 2025 Seu Nome
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
```

**5. Atualize o README.md**
```markdown
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

**6. Adicione badge (opcional)**
```markdown
![License](https://img.shields.io/badge/License-MIT-blue.svg)
```

**7. Configure arquivos do projeto**

**package.json (Node.js):**
```json
{
  "license": "MIT"
}
```

**setup.py (Python):**
```python
setup(
    license='MIT',
)
```

**Cargo.toml (Rust):**
```toml
[package]
license = "MIT"
```

**Dica:** Use identificadores SPDX (ex: "MIT", "Apache-2.0", "GPL-3.0-or-later")

</details>

<details>
<summary><b>8. Posso combinar código de projetos com licenças diferentes?</b></summary>

**Resposta:** Depende da compatibilidade entre as licenças.

**Matriz de Compatibilidade:**

**✅ COMBINAÇÕES PERMITIDAS:**
- MIT + Apache 2.0 → Resultado pode ser Apache 2.0
- MIT + BSD → Resultado pode ser BSD ou MIT
- MIT + GPL → Resultado DEVE ser GPL
- Apache 2.0 + GPL v3 → Resultado DEVE ser GPL v3
- BSD + GPL → Resultado DEVE ser GPL
- LGPL + código proprietário → Permitido via linking

**❌ COMBINAÇÕES NÃO PERMITIDAS:**
- GPL + código proprietário → Impossível
- Apache 2.0 + GPL v2 → Incompatível
- GPL v2 + GPL v3 → Incompatível (exceto se v2 especificar "or later")
- CC (Creative Commons) + código (use licenças de software!)

**Regras Práticas:**

1. **Licenças permissivas → Copyleft:** ✅ Sempre permitido
   - Você pode incorporar código MIT em projeto GPL
   - Resultado final deve ser GPL

2. **Copyleft → Permissivas:** ❌ Nunca permitido
   - Você NÃO pode incorporar código GPL em projeto MIT
   - Violação de licença

3. **Mesmo nível de permissividade:** ✅ Geralmente OK
   - MIT + BSD = OK
   - Apache + MIT = OK

**Como verificar:**
- Use ferramentas: `license-checker`, `licensecheck`, `fossology`
- Consulte [SPDX License Compatibility](https://spdx.org/licenses/)
- Em caso de dúvida, consulte advogado especializado

**Estratégia segura:**
- Documente todas as licenças de dependências
- Use apenas licenças compatíveis
- Considere criar camada de abstração para bibliotecas problemáticas

</details>

<details>
<summary><b>9. Qual a diferença entre GPL v2 e GPL v3?</b></summary>

**Principais diferenças:**

**GPL v3 adiciona (2007):**
- ✅ **Proteção contra "tivoização"** (hardware que impede modificações)
- ✅ **Termos claros sobre patentes** (proteção automática)
- ✅ **Compatibilidade com Apache 2.0**
- ✅ **Termos internacionais** (não apenas EUA)
- ✅ **Proteção contra DRM** abusivo

**GPL v2 (1991):**
- Mais antiga, ainda muito usada
- Termos de patente implícitos (não explícitos)
- Incompatível com Apache 2.0
- Foco em software, não hardware

**Exemplo de tivoização:**
- TiVo usava Linux (GPL v2) mas bloqueava modificações no hardware
- GPL v3 proíbe essa prática

**Compatibilidade:**
- GPL v2 código NÃO pode ser incluído em GPL v3 projetos
- EXCETO se especificar "GPL v2 or later"
- Linux Kernel usa especificamente GPL v2 (sem "or later")

**Qual usar hoje?**
- **GPL v3:** Padrão recomendado (proteções modernas)
- **GPL v2:** Apenas se compatibilidade com projetos antigos for crítica

</details>

<details>
<summary><b>10. O que é "viral" em licenças? GPL é realmente viral?</b></summary>

**O termo "viral" é controverso e impreciso.**

**O que críticos chamam de "viral":**
- GPL exige que trabalhos derivados também sejam GPL
- "Contamina" código proprietário em contato

**O que defensores chamam de "proteção de liberdade":**
- Garante que software livre permaneça livre
- Impede apropriação proprietária

**Realidade técnica:**

**GPL é "viral" apenas se:**
- ✅ Você modifica código GPL → Modificações devem ser GPL
- ✅ Você incorpora código GPL → Todo projeto deve ser GPL
- ✅ Você distribui binário GPL → Deve fornecer código-fonte

**GPL NÃO é "viral" se:**
- ❌ Você apenas USA software GPL (não modifica/distribui)
- ❌ Você só interage via rede (exceto AGPL)
- ❌ Você usa LGPL (permite linking com código proprietário)

**Níveis de "viralidade":**

1. **AGPL v3:** Mais "viral" (até uso via rede)
2. **GPL v3:** Viral para modificações e distribuição
3. **LGPL:** Parcialmente viral (só a biblioteca)
4. **MPL 2.0:** Viral apenas no nível de arquivo
5. **MIT/BSD/Apache:** Não viral (permissivas)

**Perspectiva legal:**
- "Viral" não é termo jurídico
- GPL é copyleft, não vírus
- Você escolhe usar ou não usar GPL

**Para desenvolvedores corporativos:**
- Se não quer "viralidade", evite GPL em produtos proprietários
- Use MIT, Apache, BSD ou LGPL
- Leia políticas da sua empresa sobre GPL

</details>

<details>
<summary><b>11. Posso relicenciar contribuições de terceiros?</b></summary>

**Resposta curta:** Não, a menos que tenha permissão explícita.

**Detalhes:**
- Cada contribuidor mantém direitos autorais sobre suas contribuições
- Você não pode mudar licença de código que não escreveu
- Mesmo sendo mantenedor do projeto

**Soluções:**

**1. Contributor License Agreement (CLA)**
- Contribuidores concedem direitos para relicenciar
- Usado por: Apache Foundation, Google, Microsoft
- Exemplo: "Eu cedo direitos para que o projeto possa mudar de licença"

**2. Copyright Assignment**
- Contribuidores transferem copyright para organização central
- Mais raro, considerado "pesado"
- Usado por: FSF (Free Software Foundation)

**3. "inbound=outbound" rule**
- Contribuição entra na mesma licença que projeto está
- Simples, mas impede mudanças de licença futuras
- Usado por: GitHub (padrão)

**Exemplo prático:**
```
# .github/CONTRIBUTING.md

## Contributor License Agreement

By submitting a pull request, you agree that:
1. Your contribution is licensed under [PROJECT LICENSE]
2. You grant us rights to relicense in the future
```

**Se não tem CLA:**
- Precisará contatar TODOS os contribuidores
- Se um contribuidor discordar, não pode mudar licença daquele código
- Alternativa: remover/reescrever código do contribuidor que discorda

</details>

<details>
<summary><b>12. Software sem licença é automaticamente open source?</b></summary>

**Resposta:** NÃO! É exatamente o oposto.

**Código sem licença significa:**
- ❌ **"Todos os direitos reservados"** (copyright padrão)
- ❌ Ninguém pode legalmente copiar
- ❌ Ninguém pode modificar
- ❌ Ninguém pode distribuir
- ❌ Usar pode ser violação de copyright

**Mesmo se estiver no GitHub público:**
- GitHub != Licença
- Público != Livre para usar
- Visível != Open source

**Termos de Serviço do GitHub concedem apenas:**
- Direito de visualizar e fazer fork dentro do GitHub
- NÃO concedem direito de usar em outros contextos

**Para ser open source, precisa:**
1. Licença explícita (MIT, GPL, Apache, etc.)
2. Que atenda critérios OSI (Open Source Initiative)
3. Arquivo LICENSE no repositório

**Ação necessária:**
- Sempre adicione uma licença
- Sem licença = não é open source
- "Grátis" ≠ "Livre" (Free as in beer ≠ Free as in freedom)

**Se você encontrou código sem licença:**
- Não use sem permissão
- Contate o autor pedindo que adicione licença
- Ou procure alternativa licenciada

</details>

</details>

---

## 📚 Recursos Adicionais

#### Sites Úteis

- **[Choose A License](https://choosealicense.com/)** - Guia interativo oficial do GitHub
- **[TLDRLegal](https://tldrlegal.com/)** - Resumos de licenças em linguagem acessível
- **[Open Source Initiative](https://opensource.org/licenses)** - Lista oficial de licenças aprovadas pela OSI
- **[GNU Licenses](https://www.gnu.org/licenses/)** - Documentação oficial das licenças GNU
- **[Creative Commons](https://creativecommons.org/)** - Portal sobre licenças Creative Commons

#### Ferramentas

- **SPDX License List** - Identificadores padronizados de licenças
- **License Finder** - Analisa dependências e licenças do projeto
- **FOSSology** - Scanner automatizado de licenças para código

---

## ⚖️ Aviso Legal

Este guia possui finalidade exclusivamente informativa e não constitui aconselhamento jurídico. Para decisões legais relevantes sobre licenciamento de software, consulte um advogado especializado em propriedade intelectual.

---

<div align="center">

**Criado com 📜 para a comunidade open source**

*Última atualização: 2025*

</div>
