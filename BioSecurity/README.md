# Documentação do Projeto: Controle de Acesso por Biometria e Localização

## Escopo do Projeto
O projeto visa desenvolver uma aplicação mobile que permita o controle de acesso de usuários através da autenticação biométrica e da verificação de localização geográfica. A aplicação só permitirá o acesso se o usuário estiver dentro da área permitida, combinando a autenticação por impressão digital com a confirmação da localização. O backend será gerenciado pelo Firebase, e o Flutter será utilizado para o desenvolvimento da interface. A aplicação será testada e implementada em dispositivos Android utilizando o Android Studio.

## Objetivos SMART

- **Específico:** Criar uma aplicação de controle de acesso que utilize autenticação biométrica e verificação de localização para garantir segurança, com gerenciamento de usuários e dados no Firebase.
  
- **Mensurável:** O sucesso será medido pela implementação das funcionalidades principais, como autenticação biométrica, verificação de localização e integração com Firebase para armazenamento e controle de dados.
  
- **Atingível:** A aplicação será desenvolvida em 1 semana, utilizando Flutter, Firebase, Geolocator e autenticação local para biometria.
  
- **Relevante:** Aumentar a segurança no controle de acesso de áreas restritas, garantindo que apenas usuários autorizados e em locais permitidos tenham acesso.
  
- **Temporal:** Lançar a versão inicial da aplicação em 7 dias.

## Cronograma

| Fase                            | Duração    | Início      | Término     |
|----------------------------------|------------|-------------|-------------|
| Configuração do Ambiente         | 1 dia      | 21/10/2024  | 21/10/2024  |
| Implementação da Autenticação    | 2 dias     | 22/10/2024  | 23/10/2024  |
| Implementação da Geolocalização  | 2 dias     | 23/10/2024  | 24/10/2024  |
| Integração com Firebase          | 1 dia      | 25/10/2024  | 26/10/2024  |
| Testes e Ajustes Finais          | 1 dia      | 27/10/2024  | 28/10/2024  |

## Análise de Risco

- **Riscos Técnicos:** Problemas de integração entre a biometria e a geolocalização ou falhas de segurança.  
  **Mitigação:** Utilizar bibliotecas confiáveis como Local Auth e Geolocator, além de seguir as melhores práticas de segurança no Firebase.

- **Riscos de Prazo:** Possíveis atrasos na implementação da autenticação biométrica em dispositivos específicos.  
  **Mitigação:** Testar desde o início em múltiplos dispositivos para garantir compatibilidade e desempenho.

- **Riscos Financeiros:** Custos com a utilização de Firebase para autenticação e banco de dados.  
  **Mitigação:** Usar o plano gratuito do Firebase durante o desenvolvimento e planejar uma migração para o plano pago conforme o aumento de usuários.

## Recursos

- **Pessoas:** 4 desenvolvedores.
- **Tecnologia:** Flutter, Firebase, Geolocator, Local Auth, Android Studio.

## Prototipagem

### Baixa Fidelidade
- #### Tela 1
<img width="357" alt="image" src="https://github.com/user-attachments/assets/231e745c-df73-439c-ad89-1174c623a0ab">

- #### Tela 2
<img width="149" alt="image" src="https://github.com/user-attachments/assets/996b127f-f122-4ca1-a8f8-727aed2711ff">


## Alta Fidelidade
- #### Tela 1
<img width="457" alt="image" src="https://github.com/user-attachments/assets/93d0d811-1b79-4e7e-a40d-b5f3aa593ec0">

- #### Tela 2
<img width="143" alt="image" src="https://github.com/user-attachments/assets/2cf4b7f2-74a6-45a1-96ec-0bed8ad99355">

- #### Tela de Configurações
<img width="160" alt="image" src="https://github.com/user-attachments/assets/e4d3e8df-2fab-45c1-ac04-84ea602d732b">

- #### Tela de localização
<img width="197" alt="image" src="https://github.com/user-attachments/assets/c805b15b-085e-4fdf-beb4-100d83a20f5b">