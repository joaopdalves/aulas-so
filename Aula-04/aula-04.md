# 🖥️ Atividade — Estrutura e Arquitetura de Sistemas Operacionais

> ##### 🏫 **Instituição:** FATEC — Faculdade de Tecnologia
> ##### 👨‍🏫 **Professor:** Prof. Me. Deivison S. Takatu
> ##### 📚 **Disciplina:** Sistemas Operacionais — Aula 04

---

![OS Terminal GIF](https://media4.giphy.com/media/JmJMzlXOiI0dq/100.gif)

> *"A maioria dos dispositivos não cria um sistema operacional do zero. Em vez disso, utilizam sistemas existentes e os adaptam para seu hardware específico."*
> — Aula 04, FATEC

---

## 🔍 Item 1 — 5 Sistemas Operacionais Derivados de Outros Sistemas

![Coding GIF](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExazhid3Z0eHp5dzM0NzE2dTF1NjlvZWVmNDR2b2FqdWw5bXF6aGtzaSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/zOvBKUUEERdNm/giphy.gif)

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

## 📊 Item 2 — Tabela Comparativa

![GIF](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWVubnEwMmF3dGhsZ2Q2M2ZtZjk0czAwcWs3cmRrN2pzbmplYjJhOSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/10mzF0YmVmZNuw/giphy.gif)

| 🖥️ Sistema Operacional | 🧱 Sistema Base | ⚙️ Kernel | 🎯 Público-Alvo | 🎨 Interface | 📦 Distribuição | ⭐ Diferencial Principal |
|---|---|---|---|---|---|---|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" width="20"/> **Android** | Linux | Linux (modificado) | Smartphones e tablets | Material Design | Open Source (AOSP) | Integração com hardware móvel, sensores e Play Store |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20"/> **macOS** | Darwin / BSD (Unix) | XNU (Mach + BSD) | Computadores Apple | Aqua | Proprietário | Integração com ecossistema Apple e hardware dedicado |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-original.svg" width="20"/> **Ubuntu** | Debian Linux | Linux | Desktops e servidores | GNOME | Open Source | Facilidade de uso, suporte LTS e grande comunidade |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20"/> **iOS** | Darwin / BSD (Unix) | XNU (Mach + BSD) | iPhones e iPads | Cocoa Touch | Proprietário | Segurança rigorosa, sandbox e otimização para hardware Apple |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg" width="20"/> **Chrome OS** | Gentoo Linux | Linux | Chromebooks / educação | Chrome Shell (Aura) | Open Source | Foco em nuvem, boot ultrarrápido e suporte a apps Android |

---

## 🧠 Item 3 — Análise e Conclusão

![GIF](https://media1.giphy.com/media/46hMzlIbVpWPJAWdUY/giphy.gif)

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