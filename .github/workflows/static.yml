<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Redirecionamento WhatsApp</title>
  <script>
    const params = new URLSearchParams(window.location.search);
    const numero = params.get('numero');
    const msg = params.get('msg');

    if (numero) {
      const mensagem = msg ? encodeURIComponent(msg) : "";
      window.location.href = `https://wa.me/${numero}?text=${mensagem}`;
    } else {
      document.addEventListener("DOMContentLoaded", () => {
        document.body.innerHTML = "<p style='color:red; text-align:center; margin-top:50px;'>Número de WhatsApp não fornecido.</p>";
      });
    }
  </script>
</head>
<body>
  <p style="text-align:center; margin-top:50px;">Redirecionando para o WhatsApp...</p>
</body>
</html>
