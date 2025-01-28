# Invitation Management System

📁 **Status do Projeto**: Arquivado  
Este repositório foi arquivado e não está mais em desenvolvimento ativo. Todo o código e a lógica contidos aqui estão disponíveis apenas para referência.

---

## 📖 Descrição

O **Invitation Management System** é uma solução completa para gerenciar e validar convites para eventos.  
Ele combina uma plataforma web baseada em **Next.js**, integração com dispositivos **Arduino** para controle físico de acessos, e um aplicativo mobile para validação dos convites no local do evento.

---

## 🚀 Funcionalidades Principais

### Plataforma Web (Next.js)
- Cadastro de eventos e convidados.
- Geração e envio de convites com QR Code.
- Painel de controle para gerenciar o status dos convidados (confirmados, pendentes, etc.).

### Integração com Arduino
- Controle de acesso físico, como abertura de portas ou catracas, sincronizado com a plataforma web.
- Validação de QR Codes diretamente no dispositivo.

### Aplicativo Mobile
- Escaneamento de QR Codes para validação rápida no local.
- Feedback em tempo real sobre o status do convite (válido, expirado, etc.).
- Sincronização com a plataforma web para manter registros atualizados.

---

## 🛠️ Tecnologias Utilizadas

### Backend e Plataforma Web
- **Framework:** [Next.js](https://nextjs.org/)
- **Linguagem:** TypeScript
- **Banco de Dados:** MongoDB
- **Autenticação:** NextAuth ou JWT
- **Comunicação com Arduino:** API RESTful ou WebSocket.

### Integração com Arduino
- **Plataforma:** Arduino Uno/ESP32
- **Comunicação:** Protocolo Serial ou HTTP (via Wi-Fi para dispositivos compatíveis).
- **Linguagem:** C++.

### Aplicativo Mobile
- **Framework:** [React Native](https://reactnative.dev/)
- **Bibliotecas:** 
  - `react-native-camera` ou `expo-camera` para leitura de QR Codes.
  - Axios para comunicação com a API.

---

## 📦 Estrutura do Projeto

```plaintext
/
├── web/                # Código da plataforma web (Next.js)
├── mobile/             # Código do aplicativo mobile (React Native)
├── arduino/            # Código para o dispositivo Arduino
├── docs/               # Documentação adicional e especificações técnicas
└── README.md           # Documentação principal do projeto

