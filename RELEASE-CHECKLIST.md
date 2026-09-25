# Checklist de lançamento Android

Antes de publicar uma nova versão:

- [ ] Confirmar versão, nome e pacote Android do app para atletas.
- [ ] Excluir VERTEX Control/Admin, código privado, credenciais e arquivos de assinatura.
- [ ] Testar instalação e abertura do APK em um Android.
- [ ] Gerar SHA-256 do APK final e registrar em `SHA256SUMS.txt`.
- [ ] Anexar APK e checksum aos ativos da Release correspondente.
- [ ] Conferir o download público e comparar o digest retornado pelo GitHub com o checksum local.
- [ ] Atualizar README e notas da Release usando o nome real dos arquivos anexados.

O SHA-256 detecta divergências no arquivo e não substitui a validação de origem e assinatura.
