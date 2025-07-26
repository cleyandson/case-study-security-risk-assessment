# Avaliação de Risco e Proposta de Hardening de Rede

## Visão Geral do Projeto

Um estudo de caso prático, desenvolvido no contexto do [Certificado Profissional de Cibersegurança do Google](https://www.coursera.org/google-certificates/cybersecurity-certificate), focado na avaliação de riscos após um incidente de segurança. O objetivo do projeto foi inspecionar a rede de uma organização que sofreu uma violação de dados, identificar as vulnerabilidades críticas e propor um plano de *hardening* eficaz para prevenir futuros ataques.

---

## O Cenário

A análise foi baseada em um incidente onde uma organização de mídia social sofreu uma grande violação de dados, que comprometeu as informações pessoais de seus clientes (nomes e endereços). Após o incidente, uma inspeção na rede revelou quatro vulnerabilidades principais que precisavam de correção imediata:

1.  **Senhas Compartilhadas:** Funcionários da organização compartilhavam senhas de acesso entre si.
2.  **Credencial Padrão:** A senha de administrador do banco de dados estava definida com o valor padrão de fábrica.
3.  **Firewalls Abertos:** Os firewalls não tinham regras implementadas para filtrar o tráfego que entrava e saía da rede.
4.  **Falta de MFA:** A autenticação multifator (MFA) não era utilizada em nenhum sistema da organização.

---

## Metodologia de Análise

Para investigar e responder ao cenário, a seguinte metodologia foi aplicada:

* **Inspeção de Rede:** Análise da configuração da rede corporativa para identificar falhas de segurança e pontos fracos que levaram ao incidente.
* **Análise de Vulnerabilidades:** Avaliação das quatro vulnerabilidades encontradas para determinar o risco e o impacto potencial de cada uma.
* **Consulta de Melhores Práticas:** Utilização de uma base de conhecimento sobre ferramentas e métodos de *hardening* para selecionar as soluções mais eficazes para as falhas identificadas.
* **Documentação Técnica:** Consolidação de todas as descobertas e recomendações em um Relatório de Avaliação de Risco de Segurança formal.

---

## Relatório de Avaliação de Risco (PDF)

O relatório completo, detalhando a análise e as justificativas técnicas para cada recomendação, pode ser encontrado no link abaixo.

* 📄 **[Relatório de Avaliação de Risco - Versão em Português (PDF)](https://github.com/cleyandson/case-study-security-risk-assessment/blob/3a013a0b29df672f39b3966fd9da31629d43a75b/Documents/%5BPT-BR%5D%20Security%20risk%20assessment%20report.pdf)**

---

## Recomendações de Hardening

Com base na análise de causa raiz, foram recomendadas as seguintes ações de remediação para mitigar os riscos encontrados:

* **Implementação de Políticas de Senhas:** Adotar as recomendações do NIST para o uso de métodos de "salting" e "hashing" em senhas. Isso impede que invasores adivinhem facilmente as senhas e soluciona diretamente o problema da credencial padrão e do compartilhamento de senhas.
* **Manutenção de Firewall:** Implementar um processo de verificação e atualização regular das configurações de segurança do firewall. As regras devem ser atualizadas para filtrar o tráfego de rede anormal e proteger contra ataques externos.
* **Habilitação da Autenticação Multifator (MFA):** Implementar a MFA como uma camada de segurança adicional. Essa medida exige que o usuário confirme sua identidade de duas ou mais maneiras, protegendo contra o acesso indevido mesmo que uma senha seja comprometida.

---

## Competências Demonstradas

Este projeto destaca as seguintes competências essenciais em cibersegurança:

-   ✅ **Avaliação de Risco de Segurança**
-   ✅ **Análise de Vulnerabilidades**
-   ✅ **Network Hardening (Reforço de Segurança de Redes)**
-   ✅ **Recomendação de Políticas e Controles de Segurança**
-   ✅ **Elaboração de Relatórios Técnicos**
-   ✅ **Análise de Causa Raiz (RCA)**

---

## Contato

* **LinkedIn:** [Cleyandson Fragoso](https://www.linkedin.com/in/cleyandson-fragoso/)
* **Email:** cleyandsontech@gmail.com
