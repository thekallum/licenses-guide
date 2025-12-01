# 📜 Guia Completo de Licenças de Software

> Um guia detalhado sobre todas as principais licenças de software, suas características, permissões e restrições.

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

Uma **licença de software** é um documento legal que define como um software pode ser usado, modificado e distribuído. Escolher a licença certa é fundamental para proteger seu trabalho e definir como outros podem interagir com seu código.

### Por que as licenças são importantes?

- **Proteção Legal:** Define seus direitos como autor
- **Clareza:** Informa aos usuários o que podem ou não fazer
- **Colaboração:** Facilita contribuições de terceiros
- **Uso Comercial:** Define se o software pode ser usado comercialmente

---

## 📊 Tipos de Licenças

As licenças de software podem ser divididas em três categorias principais:

### 1. **Licenças Permissivas (Permissive)**
- Permitem uso, modificação e redistribuição com poucas restrições
- Não exigem que trabalhos derivados usem a mesma licença
- Exemplos: MIT, BSD, Apache 2.0

### 2. **Licenças Copyleft**
- Exigem que trabalhos derivados mantenham a mesma licença
- Garantem que o software permaneça livre
- Exemplos: GPL, AGPL, MPL

### 3. **Licenças Proprietárias**
- Código fechado, uso restrito
- Geralmente requerem pagamento
- Exemplos: Microsoft EULA, Oracle License

</details>

---

## ✅ Licenças Permissivas

<details>
<summary><b>MIT License</b></summary>

**📌 Características:**
- Uma das licenças mais populares e simples
- Permite uso comercial e modificação
- Requer apenas atribuição ao autor original
- Muito usada em projetos open source

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**❌ Limitações:**
- Sem garantia
- Sem responsabilidade do autor

**📝 Exemplo de uso:**
```
Copyright (c) 2025 Seu Nome

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

**🔥 Projetos famosos:** React, Node.js, jQuery, Rails

</details>

<details>
<summary><b>BSD License (2-Clause e 3-Clause)</b></summary>

**📌 Características:**
- Similar à MIT, mas com variações
- BSD 2-Clause (Simplificada): Muito parecida com MIT
- BSD 3-Clause: Adiciona cláusula sobre uso do nome do projeto

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**❌ Restrições:**
- Não pode usar o nome dos contribuidores para promover produtos derivados (3-Clause)

**🔥 Projetos famosos:** FreeBSD, Django, Flask

</details>

<details>
<summary><b>Apache License 2.0</b></summary>

**📌 Características:**
- Mais detalhada que MIT e BSD
- Inclui concessão expressa de direitos de patente
- Requer documentação de mudanças significativas

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes
- ✓ Uso privado

**❌ Restrições:**
- Deve incluir arquivo NOTICE se existir
- Deve declarar mudanças significativas
- Proteção de marca registrada

**🔥 Projetos famosos:** Android, Apache HTTP Server, Kubernetes, Swift

</details>

<details>
<summary><b>ISC License</b></summary>

**📌 Características:**
- Funcionalmente equivalente à MIT e BSD 2-Clause
- Linguagem mais simples e moderna
- Preferida por alguns por ser mais concisa

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso privado

**🔥 Projetos famosos:** npm, OpenBSD

</details>

---

## 🔄 Licenças Copyleft

<details>
<summary><b>GNU General Public License (GPL v3)</b></summary>

**📌 Características:**
- Licença copyleft forte
- Qualquer trabalho derivado DEVE ser GPL
- Protege contra "tivoização" (hardware que impede modificações)
- Inclui proteção contra patentes

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes

**❌ Restrições:**
- ✗ Trabalhos derivados devem ser GPL
- ✗ Código-fonte deve ser disponibilizado
- ✗ Mudanças devem ser documentadas
- ✗ Não pode adicionar restrições adicionais

**🔥 Projetos famosos:** Linux Kernel, Git, GIMP, WordPress

</details>

<details>
<summary><b>GNU General Public License (GPL v2)</b></summary>

**📌 Características:**
- Versão anterior da GPL
- Menos restritiva em alguns aspectos
- Ainda muito usada

**Diferenças da v3:**
- Não tem proteção contra tivoização
- Termos de patente menos explícitos
- Compatibilidade diferente com outras licenças

**🔥 Projetos famosos:** Linux Kernel (especificamente v2)

</details>

<details>
<summary><b>GNU Lesser General Public License (LGPL)</b></summary>

**📌 Características:**
- Copyleft "fraco" ou "parcial"
- Permite linking com código proprietário
- Comum em bibliotecas

**✅ Permite:**
- ✓ Uso comercial
- ✓ Linking com código proprietário
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- ✗ Modificações na biblioteca devem ser LGPL
- ✗ Código-fonte da biblioteca modificada deve ser disponibilizado

**🔥 Projetos famosos:** Qt, GTK+, LibreOffice

</details>

<details>
<summary><b>GNU Affero General Public License (AGPL)</b></summary>

**📌 Características:**
- GPL mais restritiva
- Fecha a "brecha ASP/SaaS"
- Força disponibilização de código mesmo em uso via rede

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- ✗ Código-fonte deve ser disponibilizado mesmo para usuários de rede
- ✗ Trabalhos derivados devem ser AGPL
- ✗ Muito restritiva para uso comercial

**🔥 Projetos famosos:** MongoDB (antigamente), Mastodon, NextCloud

</details>

<details>
<summary><b>Mozilla Public License (MPL) 2.0</b></summary>

**📌 Características:**
- Copyleft "fraco" a nível de arquivo
- Permite mistura com código proprietário
- Mais flexível que GPL

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Mistura com código proprietário
- ✓ Distribuição

**❌ Restrições:**
- ✗ Arquivos MPL modificados devem permanecer MPL
- ✗ Código-fonte dos arquivos MPL deve ser disponibilizado

**🔥 Projetos famosos:** Firefox, Thunderbird, LibreOffice

</details>

<details>
<summary><b>Eclipse Public License (EPL)</b></summary>

**📌 Características:**
- Similar à MPL
- Copyleft moderado
- Popular em projetos Java

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição
- ✓ Uso de patentes

**🔥 Projetos famosos:** Eclipse IDE, OpenJ9

</details>

---

## 🔒 Licenças Proprietárias

<details>
<summary><b>End-User License Agreement (EULA)</b></summary>

**📌 Características:**
- Licença de usuário final
- Código fechado
- Uso restrito conforme termos

**✅ Geralmente permite:**
- Instalação em um número limitado de dispositivos
- Uso pessoal ou comercial (dependendo da versão)

**❌ Restrições:**
- ✗ Sem acesso ao código-fonte
- ✗ Sem modificação
- ✗ Sem redistribuição
- ✗ Geralmente requer pagamento

**Exemplos:** Microsoft Office, Adobe Photoshop, AutoCAD

</details>

<details>
<summary><b>Freeware</b></summary>

**📌 Características:**
- Grátis para uso, mas código fechado
- Não é open source
- Sem direito de modificação

**Exemplos:** WinRAR (trial perpétuo), Skype, Spotify Free

</details>

<details>
<summary><b>Shareware</b></summary>

**📌 Características:**
- Teste gratuito por tempo limitado
- Requer compra para uso contínuo
- Código fechado

**Exemplos:** WinZip, muitos jogos indie

</details>

---

## 🎨 Licenças Creative Commons

<details>
<summary><b>CC0 (Public Domain)</b></summary>

**📌 Características:**
- Domínio público
- Sem restrições
- Autor renuncia todos os direitos

**✅ Permite:** TUDO

</details>

<details>
<summary><b>CC BY (Attribution)</b></summary>

**📌 Características:**
- Requer atribuição ao autor
- Muito permissiva

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- Deve dar crédito ao autor

</details>

<details>
<summary><b>CC BY-SA (Attribution-ShareAlike)</b></summary>

**📌 Características:**
- Requer atribuição
- Copyleft - trabalhos derivados devem usar mesma licença

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

**❌ Restrições:**
- Deve dar crédito
- Derivados devem ser CC BY-SA

**🔥 Usado por:** Wikipedia, Wikimedia

</details>

<details>
<summary><b>CC BY-NC (Attribution-NonCommercial)</b></summary>

**📌 Características:**
- Requer atribuição
- Proíbe uso comercial

**❌ Restrições:**
- ✗ Sem uso comercial

</details>

<details>
<summary><b>CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)</b></summary>

**📌 Características:**
- Requer atribuição
- Proíbe uso comercial
- Copyleft

**❌ Restrições:**
- ✗ Sem uso comercial
- ✗ Derivados devem ser CC BY-NC-SA

</details>

<details>
<summary><b>CC BY-ND (Attribution-NoDerivatives)</b></summary>

**📌 Características:**
- Requer atribuição
- Proíbe modificações

**❌ Restrições:**
- ✗ Sem modificações

</details>

<details>
<summary><b>CC BY-NC-ND (Attribution-NonCommercial-NoDerivatives)</b></summary>

**📌 Características:**
- Mais restritiva das CC
- Apenas compartilhamento sem modificações
- Sem uso comercial

**❌ Restrições:**
- ✗ Sem uso comercial
- ✗ Sem modificações

</details>

---

## 🔧 Outras Licenças Importantes

<details>
<summary><b>Unlicense</b></summary>

**📌 Características:**
- Domínio público
- Sem restrições
- "Anti-licença"

**✅ Permite:** TUDO

</details>

<details>
<summary><b>WTFPL (Do What The F*** You Want To Public License)</b></summary>

**📌 Características:**
- Licença humorística mas válida
- Extremamente permissiva
- Sem restrições

**✅ Permite:** LITERALMENTE QUALQUER COISA

</details>

<details>
<summary><b>Boost Software License</b></summary>

**📌 Características:**
- Similar à MIT
- Popular em bibliotecas C++
- Muito simples

**✅ Permite:**
- ✓ Uso comercial
- ✓ Modificação
- ✓ Distribuição

</details>

<details>
<summary><b>Artistic License 2.0</b></summary>

**📌 Características:**
- Popular na comunidade Perl
- Flexível quanto a modificações

</details>

<details>
<summary><b>Zlib License</b></summary>

**📌 Características:**
- Muito permissiva
- Similar à MIT
- Popular em bibliotecas gráficas

**🔥 Projetos famosos:** zlib, libpng

</details>

<details>
<summary><b>PostgreSQL License</b></summary>

**📌 Características:**
- Similar à MIT/BSD
- Muito permissiva

**🔥 Projetos famosos:** PostgreSQL

</details>

---

## 🎯 Como Escolher uma Licença

<details>
<summary><b>📊 Fluxograma de Decisão</b></summary>

```
Você quer permitir uso comercial?
│
├─ Não → CC BY-NC-SA ou CC BY-NC
│
└─ Sim → Você quer que derivados sejam código aberto?
    │
    ├─ Sim → Você quer copyleft forte?
    │   │
    │   ├─ Sim → GPL v3 ou AGPL v3
    │   │
    │   └─ Não → MPL 2.0 ou LGPL
    │
    └─ Não → Você se importa com patentes?
        │
        ├─ Sim → Apache 2.0
        │
        └─ Não → MIT ou BSD
```

</details>

<details>
<summary><b>💡 Recomendações por Caso de Uso</b></summary>

### 🚀 Projeto Open Source Geral
**Recomendado:** MIT ou Apache 2.0
- Máxima adoção
- Permite uso comercial
- Poucas restrições

### 🛡️ Proteger Liberdade do Software
**Recomendado:** GPL v3
- Garante que permanecerá livre
- Impede apropriação proprietária

### 📚 Biblioteca/Framework
**Recomendado:** LGPL ou Apache 2.0
- Permite linking com código proprietário
- Facilita adoção

### 🌐 Aplicação Web/SaaS
**Recomendado:** AGPL v3
- Fecha brecha de rede
- Força disponibilização de código

### 📖 Documentação
**Recomendado:** CC BY ou CC BY-SA
- Apropriada para conteúdo não-código
- Permite remixagem

### 🎓 Projeto Educacional
**Recomendado:** MIT ou Unlicense
- Fácil de entender
- Mínimas restrições

</details>

---

## 📊 Comparação Rápida

| Licença | Uso Comercial | Modificação | Distribuição | Copyleft | Patentes |
|---------|---------------|-------------|--------------|----------|----------|
| **MIT** | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| **Apache 2.0** | ✅ | ✅ | ✅ | ❌ | ✅ |
| **GPL v3** | ✅ | ✅ | ✅ | ✅ Forte | ✅ |
| **LGPL** | ✅ | ✅ | ✅ | ⚠️ Fraco | ✅ |
| **AGPL v3** | ✅ | ✅ | ✅ | ✅ Muito Forte | ✅ |
| **MPL 2.0** | ✅ | ✅ | ✅ | ⚠️ Fraco | ✅ |
| **BSD 3-Clause** | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| **CC BY** | ✅ | ✅ | ✅ | ❌ | ❌ |
| **CC BY-SA** | ✅ | ✅ | ✅ | ✅ | ❌ |
| **CC BY-NC** | ❌ | ✅ | ✅ | ❌ | ❌ |
| **Unlicense** | ✅ | ✅ | ✅ | ❌ | ❌ |

**Legenda:**
- ✅ Sim / Permitido / Protegido
- ❌ Não / Não permitido / Sem proteção
- ⚠️ Parcial / Com condições

</details>

---

## ❓ Perguntas Frequentes

<details>
<summary><b>1. Posso mudar a licença do meu projeto depois?</b></summary>

Sim, mas com ressalvas:
- Você pode mudar para versões futuras
- Versões antigas mantêm a licença original
- Precisa de consentimento de todos os contribuidores

</details>

<details>
<summary><b>2. Posso usar múltiplas licenças?</b></summary>

Sim, chamado de "dual licensing":
- Exemplo: GPL para open source + licença comercial paga
- Comum em projetos que querem monetizar

</details>

<details>
<summary><b>3. GPL é incompatível com que licenças?</b></summary>

- GPL v2 é incompatível com Apache 2.0
- GPL v3 é compatível com Apache 2.0
- GPL é incompatível com código proprietário

</details>

<details>
<summary><b>4. O que significa "permissive" vs "copyleft"?</b></summary>

- **Permissive:** Permite que derivados tenham qualquer licença
- **Copyleft:** Força que derivados mantenham a mesma licença

</details>

<details>
<summary><b>5. Preciso de licença para projeto pessoal?</b></summary>

Sim! Sem licença, ninguém pode legalmente usar seu código. Se quiser compartilhar, escolha uma licença.

</details>

<details>
<summary><b>6. Posso usar código GPL no meu produto comercial?</b></summary>

Sim, mas:
- Deve disponibilizar o código-fonte
- Seu produto também deve ser GPL
- Melhor usar LGPL ou MIT para projetos comerciais

</details>

<details>
<summary><b>7. Como adicionar uma licença ao meu projeto?</b></summary>

1. Crie um arquivo chamado `LICENSE` ou `LICENSE.md`
2. Copie o texto completo da licença escolhida
3. Adicione cabeçalhos de copyright nos arquivos de código
4. Mencione a licença no README.md

</details>

<details>
<summary><b>8. Posso usar trechos de código de projetos com licenças diferentes?</b></summary>

Depende da compatibilidade:
- MIT → GPL: ✅ Sim
- GPL → MIT: ❌ Não
- Apache → GPL v3: ✅ Sim
- GPL v2 → Apache: ❌ Não

</details>

---

## 📚 Recursos Adicionais

#### Sites Úteis

- **[Choose A License](https://choosealicense.com/)** - Guia interativo do GitHub
- **[TLDRLegal](https://tldrlegal.com/)** - Resumos de licenças em linguagem simples
- **[Open Source Initiative](https://opensource.org/licenses)** - Lista oficial de licenças OSI
- **[GNU Licenses](https://www.gnu.org/licenses/)** - Documentação oficial das licenças GNU
- **[Creative Commons](https://creativecommons.org/)** - Sobre licenças CC

#### Ferramentas

- **SPDX License List** - Identificadores padronizados de licenças
- **License Finder** - Analisa dependências do projeto
- **FOSSology** - Scanner de licenças para código

---

## ⚖️ Aviso Legal

Este guia é apenas informativo e não constitui aconselhamento jurídico. Para decisões legais importantes sobre licenciamento, consulte um advogado especializado em propriedade intelectual.

---

<div align="center">

**Criado com 📜 para a comunidade open source**

*Última atualização: 2025*

</div>
