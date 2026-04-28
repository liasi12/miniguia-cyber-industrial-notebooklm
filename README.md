Miniguia de Estudos: Cibersegurança em Sistemas Industriais (OT) 

Este projeto foi desenvolvido como parte de um desafio da DIO, utilizando o NotebookLM da Google como ferramenta de aprendizagem ativa para explorar a proteção de infraestruturas críticas. 

🎯 Contexto e Objetivos 

O objetivo deste caderno temático é compreender como proteger ambientes de Tecnologia Operacional (OT), onde a segurança física (safety) e a continuidade da produção são as prioridades máximas. 

Foco: Convergência TI/TO e proteção de sistemas de controle industrial. 

Meta: Consolidar conhecimentos sobre as normas NIST SP 800-82 e IEC 62443. 

 

📚 Curadoria de Fontes 

As fontes utilizadas para alimentar o NotebookLM foram: 

NIST SP 800-82 Rev. 3: Link para o PDF Oficial (Guia de Segurança para Sistemas de Controle Industrial). 

ISA/IEC 62443 (Visão Geral): Link para o resumo da ISA (Normas para segurança de automação). 

Kaspersky ICS-CERT: Link para o Portal de Ameaças (Relatórios de ataques reais em fábricas). 

 

🧠 Engenharia de Prompts e "Cicatrizes" 

Nesta seção, documento o processo de refinamento das perguntas para extrair o máximo de precisão técnica da IA. 

❌ Fase 1: O Prompt Inicial (Vago) 

Meu Prompt: "Como posso proteger uma fábrica de ataques cibernéticos?" 

Resposta da IA: A IA sugeriu medidas genéricas de TI, como instalar antivírus e trocar senhas. 

Cicatriz (O aprendizado): Percebi que a resposta foi superficial. Em uma fábrica, um antivírus comum pode causar latência e derrubar um processo crítico. A IA ignorou a diferença fundamental entre TI e TO. 

✅ Fase 2: O Prompt Refinado (Maturidade Técnica) 

Meu Prompt: "Como proteger uma fábrica usando a norma NIST SP 800-82 e a IEC 62443, focando em defesa em profundidade e segmentação de rede?" 

Resposta da IA: A resposta evoluiu drasticamente, apresentando um plano estruturado em 6 pilares, citando o Modelo de Zonas e Conduitos, DMZ Industrial e o uso de Diodos de Dados. 

Resultado: O refinamento do prompt, incluindo normas específicas, forçou a IA a sair do senso comum e entregar um guia de engenharia de segurança real. 

 

📖 Miniguia de Estudo: Proteção Industrial (Entrega Final) 

1. Pilares da Proteção (Resumo Estruturado) 

Visibilidade Passiva: Mapear ativos sem realizar varreduras ativas que possam paralisar controladores antigos. 

Segmentação (Zonas e Conduitos): Isolar sistemas críticos em zonas e controlar rigorosamente todos os caminhos de comunicação. 

Defesa em Profundidade: Implementar DMZs entre a rede corporativa e a fábrica, além de diodos de dados para sistemas de altíssima criticidade. 

Controle de Acesso: Uso de MFA para acessos remotos e privilégio mínimo (RBAC) para operadores. 

Monitoramento Consciente: Detectar anomalias em protocolos industriais (Modbus, DNP3) que ferramentas de TI comuns não identificam. 

2. Glossário de Conceitos 

PLC (CLP): O "cérebro" das máquinas; controladores lógicos programáveis. 

Modelo Purdue: Framework que organiza a rede industrial em camadas de segurança. 

Diodo de Dados: Dispositivo físico que permite a comunicação em apenas um sentido, impedindo ataques de volta. 

Sistemas Legados: Equipamentos antigos que não suportam atualizações modernas e exigem "Patching Virtual". 

 

 
