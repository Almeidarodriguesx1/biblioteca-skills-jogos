---
name: aprimoramento-jogos-gemini
description: Analisa e aprimora jogos existentes com foco em jogabilidade, interface, áudio, gráficos 3D, desempenho e validação, adaptando o trabalho aos recursos disponíveis no Gemini.
---

# Aprimoramento de jogos

Use esta skill quando for solicitado a analisar, planejar ou melhorar um jogo. Leia as instruções do usuário e os arquivos do projeto antes de propor mudanças. Identifique a engine, as plataformas, a forma de executar e os limites de acesso do ambiente. Preserve o progresso e os comportamentos existentes, exceto quando o pedido exigir mudanças.

## Diagnóstico

1. Mapeie a entrada do jogo, as cenas, os controles, a simulação, a interface, os assets e o áudio. Identifique dependências e comandos de desenvolvimento e teste.
2. Execute o jogo e os testes disponíveis quando o ambiente permitir. Registre problemas observados, expectativas do usuário e hipóteses ainda não verificadas.
3. Priorize defeitos que impedem jogar, seguidos por clareza dos controles, estabilidade, desempenho e refinamento visual e sonoro. Defina para cada fase uma entrega jogável e critérios verificáveis.

## Implementação

- Ajuste entrada, câmera, física, colisões, dificuldade e feedback com base no comportamento medido. Preserve consistência entre taxas de quadros e teste controles disponíveis.
- Melhore composição, escala, iluminação, materiais, geometria, animação e cenários respeitando a direção artística. Revise uma cena representativa antes de replicar mudanças.
- Organize menus, HUD, pausa e configurações em torno das ações do jogador. Verifique contraste, navegação, tamanhos de tela e feedback de carregamento.
- Integre efeitos e música aos eventos do jogo. Inclua controles de volume e mute, transições suaves e tratamento de bloqueios de reprodução no navegador.
- Meça desempenho em cenas representativas. Otimize assets, texturas, chamadas de renderização e carregamento com base nos resultados.
- Reaproveite código e assets existentes. Registre origem e condições de uso dos recursos adicionados.

## Skills e ferramentas

Selecione as skills disponíveis conforme a tarefa, como threejs-game-director, threejs-gameplay-systems, threejs-aaa-graphics-builder, threejs-game-ui-designer, threejs-audio-generator, threejs-performance, threejs-asset-pipeline e threejs-qa-release. Consulte suas instruções reais e referências antes de usá-las. Se estiverem indisponíveis no Gemini, aplique o fluxo deste arquivo com as ferramentas disponíveis e informe a limitação. Para modelos Blender, consulte blender-image-to-3d quando disponível.

## Verificação e entrega

Execute testes e build apropriados. Sempre que possível, jogue os fluxos alterados no navegador, registre capturas comparáveis e confirme que os ajustes persistem. Apresente alterações, evidências, comandos para executar e limitações pendentes. Se o pedido for apenas uma análise ou plano, entregue o material solicitado sem alterar o jogo.
