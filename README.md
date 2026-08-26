# 🧭 Turistando — Infraestrutura Urbana & Turismo Inteligente

> **Explore circuitos históricos em Cidades Inteligentes auditadas.**  
> *Projeto desenvolvido para a Global Solutions — FIAP (Análise e Desenvolvimento de Sistemas)*

[![FIAP](https://img.shields.io/badge/FIAP-Global%20Solutions-ed145b.svg)](https://www.fiap.com.br/)
[![PWA](https://img.shields.io/badge/Platform-PWA%20Mobile--First-0284c7.svg)]()
[![TailwindCSS](https://img.shields.io/badge/UI-Tailwind%20CSS%20%7C%20HTML5-38bdf8.svg)]()
[![Database](https://img.shields.io/badge/Database-Oracle%20SQL%20Relational-red.svg)]()
[![LGPD](https://img.shields.io/badge/Compliance-LGPD%20%26%20Smart%20Cities-green.svg)]()

---

## 📌 Sobre o Projeto

O **Turistando** é um **PWA (Progressive Web App) Mobile-First** de infraestrutura urbana inteligente que redefine a forma como os cidadãos e turistas exploram o patrimônio histórico e cultural das cidades. 

Em vez de sobrecarregar o usuário com telas excessivas ou fazê-lo navegar por rotas inacessíveis e perigosas, a plataforma prioriza a **presença real no espaço público**, a **acessibilidade universal**, o **conforto climático** e a **segurança comunitária**.

---

## 📺 Vídeo de Demonstração

Assista ao pitch e à apresentação da solução no YouTube:  
🔗 **[Vídeo Pitch — Turistando (Global Solutions FIAP)](https://youtu.be/FXYpno0pfu8)**

---

## 📱 Demonstração das Interfaces

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="assets/login.png" width="240px" alt="Tela de Autenticação Segura" /><br />
        <b>1. Acesso & Autenticação</b><br />
        <i>Login Seguro com ID Digital Governamental e Conformidade LGPD</i>
      </td>
      <td align="center" width="33%">
        <img src="assets/roteiros.png" width="240px" alt="Roteiros Inteligentes" /><br />
        <b>2. Roteiros Inteligentes</b><br />
        <i>Rotas Climáticas, Seguras e Adaptadas à Acessibilidade</i>
      </td>
      <td align="center" width="33%">
        <img src="assets/matches.png" width="240px" alt="Matches da Região" /><br />
        <b>3. Turismo Coletivo</b><br />
        <i>Varredura de Proximidade e Grupos com Identidade Auditada</i>
      </td>
    </tr>
    <tr>
      <td align="center" width="33%">
        <img src="assets/navegacao.png" width="240px" alt="Navegação GPS Ativa" /><br />
        <b>4. Navegação & Checkpoints</b><br />
        <i>GPS em Tempo Real e Desbloqueio Georreferenciado</i>
      </td>
      <td align="center" width="33%">
        <img src="turistando/assets/modo-contemplacao.png" width="240px" alt="Modo Contemplação" /><br />
        <b>5. Modo Contemplação</b><br />
        <i>Player de Áudio Imersivo: "Olhos no Monumento"</i>
      </td>
      <td align="center" width="33%">
        <img src="assets/perfil.png" width="240px" alt="Perfil e Acessibilidade" /><br />
        <b>6. Perfil & Preferências Smart</b><br />
        <i>Carteira Estudantil Digital FIAP e Métricas de Caminhada</i>
      </td>
    </tr>
  </table>
</div>

---

## 🚀 Principais Funcionalidades

### 🎧 1. Modo Contemplação ("Olhos no Monumento")
- **Audioguia Inteligente:** Narrativas divididas em capítulos dinâmicos que contam a história do local sem prender a atenção visual do usuário à tela.
- **Áudio Ambiente Integrado:** Trilha sonora contextualizada de época para imersão histórica.
- **Desbloqueio por Proximidade:** Conteúdos e capítulos são ativados automaticamente via GPS assim que o pedestre chega ao ponto turístico.

### 🗺️ 2. Roteirização Personalizada por Prioridades
- **Rota Climática (Sombra & Conforto Térmico):** Mapeamento que prioriza calçadas arborizadas e coberturas para evitar exposição ao calor extremo.
- **Rota Segura:** Direcionamento exclusivo por vias movimentadas, policiadas e iluminadas.
- **Acessibilidade Universal:** Elimina escadarias e ladeiras íngremes do cálculo de rota, mapeando trajetos planos e rampas acessíveis.
- **Alertas Hápticos:** O celular vibra no bolso ao se aproximar de marcos históricos.

### 🤝 3. Conexões & Turismo Coletivo Seguro
- **Varredura de Proximidade Inteligente:** Pareamento de co-turistas por ritmo de caminhada, idiomas e preferências de rota (% Match).
- **Identidade Auditada:** Acesso e autenticação integrados ao **ID Digital Governamental**, mitigando fraudes e garantindo ambiente confiável.
- **Código de União Mútua (PIN):** Validação física do encontro de grupos através de código numérico de 4 dígitos.
- **Chat com Ações Rápidas:** Mensagens pré-formatadas de um toque para comunicação ágil na rua.

### 🚨 4. Protocolo de Emergência e Central SOS
- **Verificação Antidisparo:** Contagem de 3 segundos para cancelamento de toques acidentais no bolso.
- **SOS com Dados de Satélite:** Transmissão imediata de Latitude/Longitude em tempo real para as autoridades.
- **Integração com Centrais Municipais:** Notificação e envio de viaturas ou Guarda Municipal mais próxima em rota de interceptação.
- **Escuta de Áudio Ativa & Escudo Comunitário:** Gravação em nuvem e alerta para co-turistas próximos prestarem apoio.

### 🎓 5. Carteira Estudantil Digital Integrada
- Validação automática por proximidade GPS para concessão de meia-entrada em museus, centros culturais e atrações parceiras.

---

## 🗄️ Arquitetura e Modelagem de Banco de Dados

A persistência e regras de negócio da infraestrutura urbana são sustentadas por um banco de dados relacional (Oracle Database) modelado para atender aos requisitos de cidades inteligentes e conformidade com a LGPD:
