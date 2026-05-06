"# Política de Privacidade do FitKeep

**Última atualização:** 06 de junho de 2025
**Vigência:** 06 de junho de 2025

---

## 1. Introdução

Bem-vindo(a) ao **FitKeep** (o \"App\"), aplicativo de monitoramento de treinos e nutrição com inteligência artificial, desenvolvido e operado por **Giovanni Greco** (\"nós\", \"nosso\", \"Controlador\").

Levamos a sua privacidade a sério. Esta Política de Privacidade descreve, de forma transparente, **quais dados coletamos, por que coletamos, como usamos, com quem compartilhamos e quais são os seus direitos**, em conformidade com a **Lei Geral de Proteção de Dados Pessoais — Lei nº 13.709/2018 (LGPD)** e demais legislações brasileiras aplicáveis.

Ao criar uma conta, fazer login ou utilizar qualquer recurso do FitKeep, você declara ter lido, compreendido e concordado com esta Política.

---

## 2. Controlador dos Dados

| Item | Descrição |
|---|---|
| **Controlador** | Giovanni Greco |
| **País** | Brasil |
| **E-mail de contato (DPO)** | contato@fitkeep.com.br |
| **Finalidade** | Operação do aplicativo FitKeep |

Para qualquer questão sobre privacidade, exercício de direitos ou denúncias, entre em contato pelo e-mail acima.

---

## 3. Dados Pessoais que Coletamos

### 3.1. Dados fornecidos por você

| Categoria | Dados | Origem |
|---|---|---|
| **Identificação** | Nome, e-mail, foto de perfil, ID Google | Login com Google (OAuth) |
| **Perfil físico** | Idade, sexo, altura, peso, percentual de gordura, nível de atividade | Inserção manual no app |
| **Objetivos** | Meta de calorias, macros, objetivo (hipertrofia / emagrecimento / força) | Inserção manual |
| **Treinos** | Exercícios criados, séries, repetições, cargas, tempo de descanso, RPE, anotações | Inserção manual / IA |
| **Sessões de treino** | Histórico de execuções, volumes, recordes pessoais (PRs) | Geradas pelo uso |
| **Nutrição** | Refeições registradas, calorias, macronutrientes, água ingerida, suplementos | Inserção manual / leitura de código de barras / IA |
| **Medidas corporais** | Peso, gordura corporal, medidas (cintura, braço, perna, etc.) | Inserção manual |
| **Reminders** | Horário e dias para lembretes de treino, água, refeições | Inserção manual |

### 3.2. Dados coletados automaticamente

| Categoria | Dados | Finalidade |
|---|---|---|
| **Token de sessão** | Token gerado após login Google | Manter você autenticado |
| **Token de notificação push** | Identificador anônimo do dispositivo (Expo/FCM) | Enviar lembretes |
| **Logs técnicos** | Data/hora de acessos, endpoints chamados | Segurança e prevenção a fraudes |
| **Status de assinatura** | Plano (Free/Pro), data de expiração, ID de transação Google Play | Habilitar funcionalidades premium |

### 3.3. Dados sensíveis

O FitKeep **trata dados sensíveis de saúde** (peso, percentual de gordura, hábitos alimentares, frequência de exercício). Esses dados são utilizados **exclusivamente para a operação do app**, com base no seu consentimento expresso e na legítima execução do contrato de uso (artigo 11, II, \"a\" da LGPD).

### 3.4. O que NÃO coletamos

- ❌ Não coletamos sua localização precisa (GPS).
- ❌ Não acessamos seus contatos.
- ❌ Não acessamos SMS, ligações ou histórico de navegação.
- ❌ Não coletamos dados de menores de 13 anos (ver Seção 11).
- ❌ Não vendemos seus dados a terceiros.

---

## 4. Como Usamos os Seus Dados

| Finalidade | Base legal (LGPD) |
|---|---|
| Criar e manter sua conta | Execução de contrato (Art. 7º, V) |
| Personalizar treinos, dietas e sugestões | Execução de contrato + consentimento |
| Gerar treinos e cálculos nutricionais via IA (GPT-5.2 e Gemini) | Consentimento (Art. 7º, I) |
| Calcular Recordes Pessoais (PRs), platôs e sobrecarga progressiva | Execução de contrato |
| Enviar lembretes (notificações push) configurados por você | Consentimento (Art. 7º, I) |
| Processar assinaturas Pro via Google Play Billing | Execução de contrato |
| Detectar uso indevido, fraudes ou violações dos Termos | Legítimo interesse (Art. 7º, IX) |
| Cumprir obrigações legais e responder a autoridades | Cumprimento de obrigação legal (Art. 7º, II) |

---

## 5. Recursos que Acessam Sensores ou Dados do Dispositivo

| Recurso | Permissão Android/iOS | Por que precisamos |
|---|---|---|
| **Foto para análise de calorias (IA)** | Câmera + Galeria | Você tira/envia a foto da refeição; convertemos para Base64 e enviamos ao Google Gemini Vision para estimar calorias e macros. A foto **não é armazenada permanentemente** após a análise. |
| **Leitura de código de barras** | Câmera | Identificamos o produto via API pública OpenFoodFacts. Apenas o código numérico é enviado, não a imagem. |
| **Notificações push** | Notificações | Enviar seus lembretes (treino, água, refeições). Você pode desabilitar a qualquer momento nas Configurações do sistema. |

Você pode revogar qualquer permissão a qualquer momento nas Configurações do seu dispositivo.

---

## 6. Compartilhamento com Terceiros

Compartilhamos dados **estritamente necessários** com os seguintes operadores, sob acordos de proteção de dados:

| Parceiro | Dados compartilhados | Finalidade | País |
|---|---|---|---|
| **Google LLC** (OAuth) | Nome, e-mail, foto de perfil, ID Google | Autenticação | EUA |
| **Google Play Billing** | ID de transação, status da assinatura | Processar compras Pro | EUA |
| **OpenAI (GPT-5.2)** via Emergent | Texto da consulta (treino solicitado, descrição da refeição) | Geração de IA | EUA |
| **Google Gemini Vision** via Emergent | Imagem da refeição (Base64) | Análise nutricional por IA | EUA |
| **OpenFoodFacts** | Código de barras escaneado | Buscar dados nutricionais do produto | França (Open Source) |
| **Expo / FCM** | Token de notificação push (anônimo) | Entregar notificações | EUA |
| **MongoDB Atlas** | Todos os dados da conta (criptografados em repouso) | Armazenamento do banco de dados | EUA / Global |

⚠️ Esses parceiros podem armazenar dados em servidores localizados **fora do Brasil** (transferência internacional). Eles atuam com cláusulas contratuais padrão e/ou frameworks internacionais reconhecidos para garantir proteção adequada (Art. 33, IX da LGPD).

❌ **Nunca vendemos, alugamos ou trocamos seus dados pessoais com anunciantes ou data brokers.**

---

## 7. Armazenamento e Segurança

- 🔒 **Criptografia em trânsito**: todas as comunicações utilizam HTTPS/TLS 1.2+.
- 🔒 **Criptografia em repouso**: o banco de dados MongoDB Atlas armazena dados criptografados.
- 🔒 **Tokens de sessão**: armazenados localmente no dispositivo via AsyncStorage / SecureStore.
- 🔒 **Acesso restrito**: apenas o controlador e operadores autorizados têm acesso aos dados, sob NDA.
- 🔒 **Princípio do menor privilégio**: a aplicação acessa apenas os dados estritamente necessários.

Apesar das medidas de segurança adotadas, nenhuma transmissão pela internet é 100% segura. Em caso de incidente de segurança que envolva seus dados, **comunicaremos você e a ANPD em até 72 horas**, conforme o Art. 48 da LGPD.

---

## 8. Retenção dos Dados

| Categoria | Prazo de retenção |
|---|---|
| Dados da conta ativa | Enquanto sua conta estiver ativa |
| Dados após exclusão da conta | Removidos em até **30 dias** |
| Logs de segurança | Mantidos por até **6 meses** |
| Dados fiscais de pagamento | **5 anos** (obrigação legal — Art. 16, II) |

---

## 9. Seus Direitos como Titular (LGPD)

A qualquer momento, você pode solicitar gratuitamente, pelo e-mail **contato@fitkeep.com.br**:

| Direito | O que significa |
|---|---|
| ✅ **Confirmação e acesso** | Saber se tratamos seus dados e ter cópia deles |
| ✅ **Correção** | Corrigir dados incompletos, inexatos ou desatualizados |
| ✅ **Anonimização ou eliminação** | Solicitar exclusão dos dados (exceto os retidos por obrigação legal) |
| ✅ **Portabilidade** | Receber seus dados em formato estruturado (JSON) |
| ✅ **Revogação do consentimento** | Retirar autorização para tratamentos baseados em consentimento |
| ✅ **Oposição** | Opor-se a tratamento que considere irregular |
| ✅ **Informação sobre compartilhamento** | Saber com quem compartilhamos seus dados |
| ✅ **Reclamação à ANPD** | Reclamar à Autoridade Nacional de Proteção de Dados ([www.gov.br/anpd](https://www.gov.br/anpd)) |

⏱️ **Prazo de resposta**: até **15 dias** corridos.

### 9.1. Como excluir sua conta

Você pode excluir sua conta diretamente no app em **Perfil → Configurações → Excluir Conta**, ou enviando um e-mail para **contato@fitkeep.com.br** com o título \"Exclusão de Conta\". A exclusão é definitiva e remove todos os seus dados pessoais em até 30 dias.

---

## 10. Compras In-App e Google Play Billing

O FitKeep oferece a assinatura **FitKeep Pro** processada exclusivamente pelo **Google Play Billing**. Não temos acesso aos seus dados de cartão de crédito ou métodos de pagamento — esses dados são tratados diretamente pelo Google sob a [Política de Privacidade do Google](https://policies.google.com/privacy).

Recebemos apenas:
- ID da transação (anônimo)
- Status da assinatura (ativa / cancelada / expirada)
- Data de início e expiração do plano

---

## 11. Crianças e Adolescentes

O FitKeep **não é direcionado a menores de 13 anos**. Caso identifiquemos que coletamos dados de uma criança sem o consentimento dos pais ou responsáveis, excluiremos imediatamente essas informações.

Para usuários entre 13 e 17 anos, recomendamos o uso supervisionado por um responsável legal.

---

## 12. Cookies e Rastreadores

O FitKeep, como aplicativo nativo móvel, **não utiliza cookies de navegador**. Utilizamos apenas armazenamento local (`AsyncStorage`) para manter sua sessão e preferências.

❌ **Não usamos** ferramentas de rastreamento publicitário (Google Ads, Meta Pixel, etc.).

---

## 13. Inteligência Artificial

O FitKeep utiliza modelos de IA de terceiros (OpenAI GPT-5.2 e Google Gemini Vision) para:
- Gerar planos de treino personalizados
- Estimar calorias de refeições por foto
- Calcular nutrientes de uma refeição descrita em texto
- Sugerir progressão de carga
- Detectar platôs

⚠️ **Importante**: as informações geradas pela IA são **estimativas estatísticas** e **não substituem orientação profissional** de educadores físicos, nutricionistas ou médicos. Use-as como referência, sempre consulte um profissional qualificado.

Os dados enviados à IA são processados conforme as políticas de privacidade dos respectivos provedores. Não treinamos modelos de IA com seus dados.

---

## 14. Alterações nesta Política

Esta Política pode ser atualizada periodicamente. Em caso de mudanças significativas, notificaremos você dentro do app e/ou por e-mail antes da entrada em vigor. A data da \"Última atualização\" no topo deste documento sempre refletirá a versão mais recente.

O uso continuado do app após alterações representa concordância com a nova versão.

---

## 15. Legislação Aplicável e Foro

Esta Política é regida pelas **leis da República Federativa do Brasil**, em especial pela **LGPD (Lei nº 13.709/2018)**, pelo **Marco Civil da Internet (Lei nº 12.965/2014)** e pelo **Código de Defesa do Consumidor (Lei nº 8.078/1990)**.

Fica eleito o **foro da comarca de domicílio do usuário** para dirimir quaisquer controvérsias decorrentes desta Política.

---

## 16. Contato

📧 **E-mail (DPO/Privacidade)**: contato@fitkeep.com.br
👤 **Controlador**: Giovanni Greco
🌍 **País**: Brasil
📱 **App**: FitKeep — Disponível no Google Play

Para questões gerais, sugestões ou denúncias, escreva para o e-mail acima. Responderemos em até 15 dias corridos.

---

*© 2025 Giovanni Greco. Todos os direitos reservados.*
"
