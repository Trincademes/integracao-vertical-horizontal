# 📘 PROJETO DE IMPLANTAÇÃO DE REDE INDUSTRIAL  
## Indústria de Produção de Tijolos Ecológicos  

---

# 1. LEVANTAMENTO TÉCNICO E PLANO ORÇAMENTÁRIO (ATIVIDADE 1)

## 1.1 Objetivo do Projeto

Implantar uma rede industrial para automatizar e integrar os processos produtivos de uma indústria de tijolos ecológicos, permitindo:

- Monitoramento em tempo real  
- Controle automatizado da produção  
- Integração com sistema supervisório  
- Comunicação com a rede corporativa  

---

## 1.2 Equipamentos Necessários

| Item | Especificação | Finalidade |
|------|--------------|------------|
| CLP Industrial | 14 entradas digitais / 10 saídas digitais | Controle do processo produtivo |
| IHM | Tela 7" touch industrial | Interface operador-máquina |
| Switch Industrial | 8 portas Ethernet IP65 | Comunicação entre dispositivos |
| Sensores | Umidade, nível e proximidade | Monitoramento do processo |
| Computador Industrial | i5 / 8GB RAM / SSD | Supervisão e SCADA |
| Licença SCADA | Software supervisório | Monitoramento e relatórios |
| Firewall Industrial | Proteção de rede | Segurança cibernética |
| Cabeamento Industrial | Cat6 industrial blindado | Comunicação de dados |

---

## 1.3 Orçamento Estimado

| Item | Quantidade | Valor Unitário | Total |
|------|------------|---------------|--------|
| CLP | 1 | R$ 4.500 | R$ 4.500 |
| Switch Industrial | 1 | R$ 3.200 | R$ 3.200 |
| IHM | 1 | R$ 3.500 | R$ 3.500 |
| Licença SCADA | 1 | R$ 8.000 | R$ 8.000 |
| Sensores | — | R$ 3.000 | R$ 3.000 |
| Cabeamento | — | R$ 2.500 | R$ 2.500 |

### 💰 Investimento Total Estimado: **R$ 24.700,00**

---

# 2. COMPARATIVO DE FORNECEDORES (ATIVIDADE 2)

## 2.1 CLP Industrial

| Fornecedor | Valor |
|------------|-------|
| Fornecedor A | R$ 4.500 |
| Fornecedor B | R$ 4.950 |

## 2.2 IHM

| Fornecedor | Valor |
|------------|-------|
| Fornecedor A | R$ 3.200 |
| Fornecedor B | R$ 3.450 |

## 2.3 Switch Industrial

| Fornecedor | Valor |
|------------|-------|
| Fornecedor A | R$ 3.200 |
| Fornecedor B | R$ 3.450 |

## 2.4 Sensores

| Tipo | Fornecedor A | Fornecedor B |
|------|-------------|-------------|
| Umidade | R$ 480 | R$ 520 |
| Nível | R$ 390 | R$ 430 |
| Proximidade | R$ 150 | R$ 180 |

## 2.5 Análise Técnica dos Equipamentos

Os equipamentos selecionados atendem aos seguintes critérios:

- Grau de proteção industrial (IP65 ou superior)
- Resistência a poeira e vibração
- Comunicação Ethernet/Profinet
- Compatibilidade com sistemas supervisórios
- Possibilidade de expansão futura

A solução permite integração com sistemas corporativos via banco de dados e ERP.

---

# 3. ANÁLISE DE VIABILIDADE TÉCNICA E ECONÔMICA (ATIVIDADE 3)

## 3.1 Viabilidade Técnica

A solução proposta é tecnicamente viável pois:

- Utiliza protocolos industriais consolidados
- Permite integração futura com sistemas ERP
- Suporta expansão modular
- Possui estrutura escalável

---

## 3.2 Viabilidade Econômica

### Benefícios Esperados:

- Redução de falhas operacionais
- Redução de retrabalho
- Aumento da produtividade
- Monitoramento em tempo real
- Melhoria na tomada de decisão

### Estimativa de Retorno (ROI)

Com a redução de desperdícios e aumento da eficiência produtiva, estima-se retorno do investimento em médio prazo (12 a 24 meses).

---

## 3.3 Riscos Envolvidos

- Dependência de fornecedores específicos
- Necessidade de treinamento da equipe
- Risco de falhas de rede
- Investimento inicial elevado

---

# 4. DIAGRAMA DA ARQUITETURA DA REDE (ATIVIDADE 4)

## 4.1 Arquitetura Proposta

flowchart TD
    A[Rede Corporativa]
    B[Firewall Industrial]
    C[Switch Industrial]

    D[CLP]
    E[Computador]
    F[IHM]

    G[Sensores]
    H[Sistema SCADA]
    I[Atuadores / Motores]

    A --> B --> C
    C --> D
    C --> E
    C --> F

    D --> G --> I
    E --> H
```

---

## 4.2 Descrição da Arquitetura

- O CLP controla sensores e atuadores.
- A IHM permite interação do operador.
- O Switch Industrial interliga todos os dispositivos.
- O Computador executa o sistema supervisório SCADA.
- O Firewall garante segurança na comunicação com a rede corporativa.
- A estrutura permite expansão com novos CLPs e switches.

---

## 4.3 Planta Baixa da Fábrica de Tijolos Ecológicos

### Visão Geral da Estrutura

A planta baixa da fábrica foi desenvolvida para representar a organização física dos setores produtivos e dos sistemas de automação industrial implementados.

A estrutura contempla:

- Área de mistura (Misturador de solo e cimento)
- Esteira transportadora
- Prensa hidráulica
- Sensores de umidade, nível e proximidade
- Motores trifásicos
- Pilhas de tijolos (armazenamento)
- Painel elétrico principal
- CLP
- IHM
- Switch industrial
- Área de supervisão com sistema SCADA
- Integração com rede corporativa

---

###  Layout da Planta


![Planta Baixa da Fábrica](/Aula3/plantabaixa.png)

---

### Organização da Infraestrutura

A disposição dos equipamentos foi planejada para:

- Garantir fluxo contínuo de produção
- Minimizar cabeamento excessivo
- Facilitar manutenção preventiva
- Permitir expansão futura da linha de produção
- Manter separação entre área industrial e supervisão

---

### Estrutura de Comunicação

A comunicação ocorre da seguinte forma:

- Sensores → CLP  
- CLP → Switch Industrial  
- Switch → IHM e Sistema SCADA  
- SCADA → Rede Corporativa (via Firewall)

A arquitetura permite futura inclusão de:

- Novos CLPs
- Ampliação da rede Ethernet industrial
- Integração com ERP
- Monitoramento remoto

---



# CONCLUSÃO

A implantação da rede industrial na indústria de tijolos ecológicos proporciona:

- Modernização do processo produtivo
- Maior controle operacional
- Redução de desperdícios
- Melhoria da eficiência
- Base tecnológica para crescimento futuro

O investimento estimado de R$ 24.700,00 é justificado pelos ganhos operacionais e estratégicos que a automação proporciona.

---

