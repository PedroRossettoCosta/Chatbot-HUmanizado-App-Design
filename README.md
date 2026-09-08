# Chatbot Humanizado — App Design

Repositório de design (TCC) para uma plataforma de assistente conversacional humanizado voltado à saúde mental, pensada para apoiar psicólogos, psicanalistas e terapeutas na triagem, acolhimento e acompanhamento de pacientes via canais de mensagens (WhatsApp, Instagram etc.).

Os arquivos aqui são exports do [Stitch](https://stitch.withgoogle.com) (ferramenta de design da Google): cada tela vem com o código-fonte (`code.html`) e uma captura (`screen.png`), e cada produto tem um `DESIGN.md` descrevendo o design system (cores, tipografia, espaçamento, componentes) usado nas telas.

## Estrutura

O repositório separa as duas frentes do produto:

### `stitch_painel_chatbot_sa_de_mental_web/` — Painel Web (Serenia)
Painel administrativo para o profissional configurar e monitorar o assistente de IA (Maria/Serenia) que conversa com os pacientes.

- `serene_clinical_intelligence/DESIGN.md` — design system do painel web
- `serenia_landing_page_institucional/`, `maria_landing_page_institucional/` — landing pages institucionais
- `serenia_login_cadastro/` — login e cadastro
- `serenia_dashboard_principal/` — dashboard principal
- `serenia_conversas_multicanal/` — conversas multicanal (WhatsApp/Instagram)
- `serenia_alertas_de_seguran_a/` — alertas de segurança/crise
- `serenia_planos_contrata_o/`, `serenia_assinatura_inativa_reativa_o/` — planos e assinatura
- `maria_ai_clinical_intake_triage_platform/` — plataforma de triagem clínica da IA
- `maria_logo/`, `logo_serenia_assistente_terap_utico/` — logos
- `close_up_portrait_of_a_warm_friendly_female_clinical_psychologist_in_her_30s/` — imagem de persona

### `stitch_psicompanion_mobile_app/` — App Mobile (Serena Clínico)
Aplicativo mobile para o terapeuta acompanhar pacientes e sessões no dia a dia, com navegação inferior de 4 abas (Agenda, Pacientes, Alertas, Perfil).

- `serena_cl_nico/DESIGN.md` — design system do app mobile
- `in_cio_serena_cl_nico/` — tela inicial
- `agenda_serena_cl_nico/` — agenda
- `conversas_serena_cl_nico/` — conversas
- `alertas_de_seguran_a_serena_cl_nico/` — alertas de segurança/crise
- `maria_cl_nico_flow/` — fluxo do assistente Maria no app
- `serena_cl_nico_logo/` — logo
- `warm_friendly_and_professional_portrait_headshot_of_a_brazilian_female/` — imagem de persona

## Sobre o design

Ambos os produtos seguem uma mesma linha visual — **minimalismo orgânico e acolhedor**, com tons quentes/naturais, cantos arredondados e tipografia Plus Jakarta Sans — mas com design systems próprios (paletas e escalas específicas) documentados em cada `DESIGN.md`. Um cuidado especial é dado aos estados de **alerta de crise/segurança**, tratados com contraste e hierarquia visual claros em ambas as plataformas.

## Uso

Cada `code.html` é autocontido e pode ser aberto diretamente no navegador para visualizar a tela.
