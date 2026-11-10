# pumpsaude.com.br

Site estático da Pump Saúde, publicado no Netlify (projeto singular-marzipan-7ea5b8).

- Sem etapa de build. Pasta publicada: raiz do repositório.
- Formulário "proposta" usa Netlify Forms. Página de retorno: /obrigado.
- Cada envio vira e-mail para contato@pumpsaude.com.br pela notificação de formulário do Netlify (Project configuration > Notifications > Emails and webhooks > Form submission notifications). Remetente formresponses@netlify.com: não trocar por remetente @pumpsaude.com.br, o DMARC do domínio rejeita.
- Assunto vem do campo oculto `subject` ("[Site Pump Saúde] Novo contato: nome"). O Reply-To vem do campo `email`.
