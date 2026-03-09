# 🖥️ Atividade — Estrutura e Arquitetura de Sistemas Operacionais

> #### 🏫 **Instituição:** FATEC — Faculdade de Tecnologia
> #### 👨‍🏫 **Professor:** Prof. Me. Deivison S. Takatu
> #### 📚 **Disciplina:** Sistemas Operacionais — Aula 04

---

![GIF](https://media4.giphy.com/media/JmJMzlXOiI0dq/100.gif)

> *"A maioria dos dispositivos não cria um sistema operacional do zero. Em vez disso, utilizam sistemas existentes e os adaptam para seu hardware específico."*

---

## 🔍 Item 1 — 5 Sistemas Operacionais Derivados de Outros Sistemas

![GIF](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWVubnEwMmF3dGhsZ2Q2M2ZtZjk0czAwcWs3cmRrN2pzbmplYjJhOSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/10mzF0YmVmZNuw/giphy.gif)
---

### 1. 🤖 Android — baseado no Kernel Linux

O Android, desenvolvido pelo Google, utiliza o kernel Linux como base. O sistema foi adaptado para dispositivos móveis com toque, sensores e conectividade constante, adicionando uma camada de runtime própria (ART — Android Runtime) e uma interface gráfica completamente redesenhada para smartphones e tablets.

---

### 2. 🍎 macOS — baseado no Darwin/BSD (Unix)

O macOS da Apple é construído sobre o Darwin, que por sua vez deriva do BSD (Berkeley Software Distribution), uma variação do Unix. A Apple adaptou esse núcleo robusto adicionando sua interface gráfica Aqua, ferramentas proprietárias e integração com o ecossistema Apple (iCloud, iPhone, etc.).

---

### 3. 🟠 Ubuntu — baseado no Debian Linux

O Ubuntu, desenvolvido pela Canonical, é uma distribuição Linux derivada do Debian. Mantém o sistema de pacotes APT e a base Debian, mas adiciona um ciclo de lançamentos previsível (a cada 6 meses), suporte LTS (Long Term Support) e uma experiência de usuário mais acessível, sendo amplamente utilizado em desktops e servidores.

---

### 4. 📱 iOS — baseado no Darwin/BSD (Unix) / XNU Kernel

O iOS, sistema operacional da Apple para iPhones e iPads, compartilha o mesmo kernel (XNU) e base Darwin do macOS. Apesar da origem comum, o iOS foi profundamente adaptado para hardware com recursos limitados de bateria, tela sensível ao toque e foco em segurança e privacidade móvel, com uma sandbox rigorosa para aplicativos.

---

### 5. 🌐 Chrome OS — baseado no Kernel Linux / Gentoo

O Chrome OS, desenvolvido pelo Google para Chromebooks, é baseado no kernel Linux e deriva da distribuição Gentoo Linux. O sistema foi adaptado para funcionar com foco em navegação web, armazenamento em nuvem e inicialização extremamente rápida, substituindo aplicativos tradicionais por Progressive Web Apps (PWAs) e aplicativos Android (via Play Store).

---

## 🎮 Sistemas Operacionais de Consoles

![GIF](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExazhid3Z0eHp5dzM0NzE2dTF1NjlvZWVmNDR2b2FqdWw5bXF6aGtzaSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/zOvBKUUEERdNm/giphy.gif)

Os consoles modernos também são exemplos práticos de reaproveitamento de estruturas de sistemas operacionais existentes, adaptados para o contexto de jogos com foco em desempenho gráfico, latência mínima e experiência imersiva.

---

### 6. 🟩 Xbox Series X|S — Microsoft Game OS

O **Microsoft Game OS** é o sistema operacional das consolas Xbox Series X e Series S. Baseado no **Windows NT**, ele é uma versão profundamente customizada do núcleo Windows, otimizada para jogos com suporte a DirectX 12 Ultimate, ray tracing e carregamento ultrarrápido via SSD NVMe personalizado (Velocity Architecture). Utiliza um modelo de dual-OS: um lado cuida da interface e jogos, o outro gerencia serviços em segundo plano como o Xbox Game Pass e o Game DVR.

---

### 7. 🔵 PlayStation 5 — Orbis OS

O **Orbis OS** é o sistema operacional do PlayStation 4 e 5, desenvolvido pela Sony. É baseado no **FreeBSD**, uma distribuição Unix de código aberto. A Sony adaptou profundamente o FreeBSD para suportar arquitetura x86-64 personalizada (nos consoles mais recentes com AMD), APIs gráficas proprietárias (GNM/GNMX), e recursos exclusivos como o temporizador háptico do DualSense. Por ser derivado do FreeBSD, mantém características como estabilidade, segurança e gerenciamento eficiente de memória.

---

### 8. 🔴 Nintendo Switch — Horizon OS (HOS)

O **Horizon OS** (também chamado de **HOS**) é o sistema operacional desenvolvido internamente pela Nintendo para o Switch. Diferentemente dos concorrentes, a Nintendo criou seu próprio microkernel, sem usar como base um sistema consolidado como Linux ou BSD. O HOS é um sistema leve e modular, projetado para gerenciar tanto o modo portátil (handheld) quanto o modo TV do Switch, com transição fluida entre os dois. Suporta multiplayer local, online via Nintendo Switch Online, e a eShop.

---

### 9. 🖤 Steam Deck — SteamOS 3 (Arch Linux)

O **SteamOS 3** é o sistema operacional do Steam Deck, desenvolvido pela Valve. É baseado no **Arch Linux**, uma distribuição rolling release do Linux. A Valve adaptou o sistema para rodar no hardware personalizado AMD APU do Steam Deck, integrando o **KDE Plasma** como ambiente gráfico no modo desktop e o **Gamescope** como compositor Wayland no modo gaming. Utiliza o **Proton** (camada de compatibilidade baseada no Wine + DXVK) para rodar jogos nativos do Windows no Linux, tornando-se um exemplo notável de adaptação de um sistema open source para uso em hardware de consumo.

---

## 🚗 Sistemas Embarcados — Apple CarPlay e Android Auto

Os sistemas embarcados automotivos representam uma das fronteiras mais recentes do reaproveitamento de infraestrutura de sistemas operacionais, levando para dentro dos veículos plataformas já consolidadas em smartphones.

---

### 10. 🍎 Apple CarPlay — baseado no iOS / Core Foundation

O **Apple CarPlay** é um sistema embarcado da Apple que projeta uma interface simplificada do iOS na central multimídia do veículo. Não é um sistema operacional completo independente: ele roda como uma extensão do iPhone conectado (via cabo Lightning/USB-C ou sem fio via Wi-Fi + Bluetooth), utilizando o kernel **XNU** e o framework **Core Foundation** do iOS. A central do carro age como um display remoto, enquanto o processamento é feito pelo próprio iPhone. Suporta aplicativos nativos como Maps, Music, Phone, Messages e apps de terceiros compatíveis (Spotify, WhatsApp, Waze, etc.).

---

### 11. 🤖 Android Auto — baseado no Android (Kernel Linux)

O **Android Auto** é a resposta do Google ao CarPlay. Assim como o CarPlay, ele projeta uma interface otimizada para direção a partir do smartphone Android conectado ao veículo. O processamento ocorre no telefone, usando o **kernel Linux** e o runtime **ART** do Android. A interface é simplificada, com botões grandes, comandos de voz via Google Assistente e integração com Google Maps, Spotify, WhatsApp e outros apps compatíveis. Existe também o **Android Automotive OS (AAOS)**, uma versão completamente embarcada que roda diretamente no hardware do veículo sem necessitar de smartphone, como nos carros Volvo, Polestar e alguns modelos GM.

---

## 📊 Item 2 — Tabela Comparativa

| 🖥️ Sistema Operacional | 🧱 Sistema Base | ⚙️ Kernel | 🎯 Público-Alvo | 🎨 Interface | 📦 Distribuição | ⭐ Diferencial Principal |
|---|---|---|---|---|---|---|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" width="20"/> **Android** | Linux | Linux (modificado) | Smartphones e tablets | Material Design | Open Source (AOSP) | Integração com hardware móvel, sensores e Play Store |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20"/> **macOS** | Darwin / BSD (Unix) | XNU (Mach + BSD) | Computadores Apple | Aqua | Proprietário | Integração com ecossistema Apple e hardware dedicado |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-original.svg" width="20"/> **Ubuntu** | Debian Linux | Linux | Desktops e servidores | GNOME | Open Source | Facilidade de uso, suporte LTS e grande comunidade |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20"/> **iOS** | Darwin / BSD (Unix) | XNU (Mach + BSD) | iPhones e iPads | Cocoa Touch | Proprietário | Segurança rigorosa, sandbox e otimização para hardware Apple |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg" width="20"/> **Chrome OS** | Gentoo Linux | Linux | Chromebooks / educação | Chrome Shell (Aura) | Open Source | Foco em nuvem, boot ultrarrápido e suporte a apps Android |
| <img src="https://www.svgrepo.com/show/473838/xbox.svg" width="20"/> **Microsoft Game OS** | Windows NT | NT Kernel (modificado) | Xbox Series X\|S | Xbox Shell | Proprietário | Dual-OS, DirectX 12 Ultimate, Velocity Architecture |
| <img src="https://cdn.simpleicons.org/playstation/003087" width="20"/> **Orbis OS** | FreeBSD (Unix) | FreeBSD Kernel | PlayStation 4 / 5 | PlayStation UI | Proprietário | APIs gráficas proprietárias GNM/GNMX, suporte ao DualSense |
| <img src="https://www.svgrepo.com/show/443280/brand-nintendo-switch.svg" width="20"/> **Horizon OS** | Microkernel próprio | Microkernel Nintendo | Nintendo Switch | Nintendo UI | Proprietário | Modo portátil + TV, leveza e modularidade |
| <img src="https://cdn.simpleicons.org/steamdeck/1A9FFF" width="20"/> **SteamOS 3** | Arch Linux | Linux | Steam Deck | KDE Plasma / Gamescope | Open Source | Compatibilidade com jogos Windows via Proton, hardware AMD |
| <img src="https://www.svgrepo.com/show/303290/apple-carplay-icon-logo.svg" width="20"/> **Apple CarPlay** | iOS / Darwin | XNU (via iPhone) | Veículos com central multimídia | CarPlay UI | Proprietário | Extensão do iPhone no carro, zero processamento embarcado |
| <img src="https://cdn.simpleicons.org/androidauto/3DDC84" width="20"/> **Android Auto** | Android (Linux) | Linux (via smartphone) | Veículos com central multimídia | Android Auto UI | Open Source | Google Assistente integrado, AAOS para uso sem smartphone |

---

## 🧠 Item 3 — Análise e Conclusão

<img src="https://media.tenor.com/_6N6J2xPY_wAAAAj/tux-linux.gif" width="200">

A pesquisa evidencia que o reaproveitamento de sistemas operacionais existentes é uma prática consolidada na indústria de tecnologia. As principais vantagens observadas são:

- 💰 **Redução de custo de desenvolvimento:** evita reconstruir do zero componentes já maduros e testados.
- 🛡️ **Maior estabilidade e segurança:** sistemas como Linux e BSD possuem décadas de refinamento e correções de segurança.
- ♻️ **Reutilização de tecnologias existentes:** drivers, bibliotecas e ferramentas já disponíveis podem ser aproveitados diretamente.
- 🔄 **Suporte e atualizações contínuas:** comunidades ativas e ciclos de atualização regulares beneficiam todos os sistemas derivados.

> 🐧 O **Linux** demonstra ser a base mais versátil da atualidade: está presente em smartphones (**Android**), Chromebooks (**Chrome OS**), servidores (**Ubuntu**) e dispositivos embarcados (**Raspberry Pi OS**), confirmando a importância de uma arquitetura de kernel bem projetada e de código aberto.

---

## 📚 Referências

- 📖 TANENBAUM, Andrew S.; BOS, Herbert. *Sistemas Operacionais Modernos*. 4. ed. São Paulo: Pearson, 2016.
- 📖 SILBERSCHATZ, Abraham; GALVIN, Peter B.; GAGNE, Greg. *Fundamentos de Sistemas Operacionais*. 9. ed. Rio de Janeiro: LTC, 2015.
- 📖 STALLINGS, William. *Sistemas Operacionais: Conceitos e Projetos*. 8. ed. São Paulo: Pearson, 2015.
- 📖 DOWNEY, Allen B. *Think OS: A Brief Introduction to Operating Systems*. Green Tea Press, 2015.
- 🔗 Google. *Android Open Source Project (AOSP)*. Disponível em: https://source.android.com
- 🔗 Apple Inc. *Apple Developer Documentation — XNU Kernel*. Disponível em: https://developer.apple.com
- 🔗 Canonical Ltd. *Ubuntu Documentation*. Disponível em: https://ubuntu.com/docs
- 🔗 Google. *Chrome OS Documentation*. Disponível em: https://www.chromium.org/chromium-os

---