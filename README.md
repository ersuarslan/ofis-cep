# Claude Ofis — telefon uygulaması

Bu depo, kişisel bir ofis panelinin telefon uygulaması kabuğudur.
`veri.json` dosyası şifrelidir (PBKDF2-SHA256 + AES-256-CBC + HMAC-SHA256); şifreyi bilmeyen kimse içeriğini okuyamaz.
Dosyalar sahibinin bilgisayarındaki köprü tarafından otomatik güncellenir; elle değiştirmeyin.
