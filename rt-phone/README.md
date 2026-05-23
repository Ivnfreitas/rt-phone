# RT Phone — Sistema de Gestão

Sistema de gestão para lojas de iPhone e produtos Apple.
 
## Deploy na Vercel

1. Acesse https://vercel.com e crie uma conta gratuita
2. Clique em "Add New Project"
3. Arraste a pasta rt-phone para a área de upload (ou conecte ao GitHub)
4. Clique em "Deploy"
5. Aguarde 1-2 minutos — o sistema estará no ar

## Configurar domínio personalizado (app.ivndigital.com)

1. No painel da Vercel, vá em "Settings > Domains"
2. Adicione: app.ivndigital.com
3. Na Hostinger, vá em "Domains > DNS Zone"
4. Adicione um registro CNAME:
   - Host: app
   - Aponta para: cname.vercel-dns.com
5. Aguarde até 24h para propagar

## Criar sua conta de admin

1. Acesse o sistema no link gerado pela Vercel
2. Clique em "Criar conta"
3. Preencha nome da loja, e-mail e senha
4. Confirme o e-mail (Supabase envia um link)
5. Acesse o sistema

## Supabase

- URL: https://mkrrtvqzuipjvsshjvjn.supabase.co
- Painel: https://supabase.com/dashboard/project/mkrrtvqzuipjvsshjvjn

## Tecnologias

- Frontend: HTML + CSS + JavaScript
- Banco de dados: Supabase (PostgreSQL)
- Hospedagem: Vercel
- Domínio: Hostinger
