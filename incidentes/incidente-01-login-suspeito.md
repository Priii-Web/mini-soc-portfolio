# Incidente 01 – Tentativa de Login Suspeito

## 📌 Descrição do Incidente
Foi identificado um comportamento anômalo relacionado a tentativas de login em um sistema corporativo. O usuário relatou falha de acesso, enquanto os logs indicaram múltiplas tentativas consecutivas em curto intervalo de tempo.

## 🕵️‍♀️ Tipo de Incidente
- Acesso não autorizado
- Tentativa de força bruta
- Comprometimento de credenciais (possível)

## 🚨 Classificação
- Severidade: Média
- Categoria: Segurança da Informação
- Domínio: Identidade e Acesso (IAM)

## 📊 Evidências Coletadas
- Endereço IP de origem desconhecida
- Horário fora do padrão do usuário
- Múltiplas tentativas de login falhas
- Usuário válido existente no sistema

## 🛠️ Ações Realizadas (Nível SOC 1)
- Registro e categorização do incidente
- Validação do usuário afetado
- Análise inicial de logs de autenticação
- Escalonamento para SOC Nível 2
- Recomendação de redefinição de senha

## 🔐 Medidas Preventivas Sugeridas
- Implementação de MFA (Autenticação Multifator)
- Monitoramento contínuo de tentativas de login
- Políticas de bloqueio por tentativas falhas
- Conscientização do usuário (engenharia social)

## 📚 Aprendizados Técnicos
Este incidente reforça a importância do monitoramento de eventos de autenticação, correlação de logs e atuação rápida do SOC para evitar comprometimento de contas.

## 🧠 Ferramentas Relacionadas
- SIEM (ex: Splunk, Wazuh)
- Logs de autenticação
- Controle de Identidade e Acesso (IAM)

---
📅 Projeto acadêmico – Mini SOC  
🎓 Área: Cibersegurança / SOC / Blue Team
