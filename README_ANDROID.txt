OBREX LOCAL 2.0 — ANDROID

Versão otimizada para uso local no Android.

PRINCIPAIS MELHORIAS
- IndexedDB dedicado para os dados.
- Comprovantes (imagem/PDF) armazenados como arquivos Blob no IndexedDB, sem transformar tudo em base64 na memória da interface.
- Migração automática dos comprovantes da versão anterior quando possível.
- Backup JSON inclui também os arquivos anexados.
- Restauração recria os arquivos no armazenamento local.
- Exclusão de pagamento/obra remove também o arquivo associado.
- Solicitação de armazenamento persistente quando o navegador permitir.
- Layout otimizado para toque, telas estreitas, recorte de câmera/notch e área segura do Android.
- PWA com cache offline e botão de instalação quando o navegador oferecer.

INSTALAÇÃO
1. Publique esta pasta em um endereço HTTPS (por exemplo, GitHub Pages).
2. Abra o endereço no Chrome Android.
3. Use “Instalar aplicativo” ou “Adicionar à tela inicial”.
4. Depois de instalado, o Obrex pode funcionar sem internet.

IMPORTANTE
Os dados e comprovantes são locais neste aparelho. O endereço HTTPS serve para entregar o aplicativo e atualizar sua versão; ele não transforma automaticamente os dados em nuvem.
Faça backups periódicos pelo menu Backup.
