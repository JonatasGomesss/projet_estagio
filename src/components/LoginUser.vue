<template>
  <div>
        <!-- Header -->
        

    <!-- Seção de Contato -->
    <section class="contact-container">
        <h2>Contact us</h2>
        <form>
            <input type="text" name="name" placeholder="Name" required>
            <input type="email" name="email" placeholder="Email" required>
            <textarea name="message" rows="5" placeholder="Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

  </div>
</template>

<script lang="ts" setup>

</script>

<style scoped>
        /* Importação de ícones */
        @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');

        /* Reset Global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        /* Container Principal */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }

        /* Títulos */
        h1 {
            text-align: center;
            margin-bottom: 1rem;
            font-size: 2rem;
        }

        .subtitulo {
            text-align: center;
            font-size: 1rem;
            color: #777;
            margin-bottom: 2rem;
        }

        /* Benefícios - Cards */
        .cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5rem;
        }

        .card {
            width: 250px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            overflow: hidden;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .card img {
            width: 100%;
            height: 140px;
            object-fit: cover;
        }

        .card .descricao {
            padding: 1rem;
            font-size: 1rem;
            text-align: center;
            color: #555;
        }

        .link {
            display: block;
            text-align: center;
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
            border-top: 1px solid #ddd;
            padding: 0.8rem 0;
            transition: color 0.3s ease;
        }

        .link:hover {
            color: #0056b3;
        }

        /* Formulário */
        .formulario {
            max-width: 600px;
            margin: 3rem auto;
            padding: 2rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .formulario input,
        .formulario button {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }

        .formulario button {
            background-color: #333;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .formulario button:hover {
            background-color: #555;
        }

        .termos {
            text-align: center;
            font-size: 0.9rem;
            color: #666;
        }

        .termos a {
            color: #007BFF;
            text-decoration: underline;
        }

        /* Rodapé */
        footer {
            text-align: center;
            margin-top: 3rem;
            color: #666;
        }

        .footer-content {
            display: flex;
            justify-content: space-around;
            padding: 1rem;
            border-top: 1px solid #ddd;
        }

        .footer-content ul {
            list-style: none;
        }

        .footer-content ul li a {
            text-decoration: none;
            color: #333;
            transition: color 0.3s ease;
        }

        .footer-content ul li a:hover {
            color: #007BFF;
        }

        .social a {
            font-size: 1.5rem;
            color: #333;
            margin: 0 0.5rem;
            transition: color 0.3s ease;
        }

        .social a:hover {
            color: #007BFF;
        }

        .copyright {
            margin-top: 1rem;
        }
 /* Reset básico */
 * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            text-align: center;
            line-height: 1.6;
        }

        /* Container principal */
        .testimonial-container {
            position: relative;
            margin: 4rem auto;
            max-width: 700px;
            padding: 2rem 1.5rem;
            background: #fff;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        /* Setas de navegação */
        .nav-arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            font-size: 1.5rem;
            color: #ccc;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .nav-arrow:hover {
            color: #555;
        }

        .nav-arrow.left {
            left: -2rem;
        }

        .nav-arrow.right {
            right: -2rem;
        }

        /* Ícone circular no topo */
        .testimonial-icon {
            display: flex;
            justify-content: center;
            margin-bottom: 1.5rem;
        }

        .testimonial-icon span {
            display: inline-block;
            width: 50px;
            height: 50px;
            background-color: #e0e0e0;
            border-radius: 50%;
        }

        /* Texto do Testemunho */
        .testimonial-text {
            font-size: 1rem;
            color: #555;
            margin: 0 1rem 1rem;
        }

        .testimonial-author {
            font-weight: bold;
            font-size: 1rem;
            color: #333;
            margin-bottom: 0.3rem;
        }

        .testimonial-company {
            font-size: 0.9rem;
            color: #777;
        }

        /* Título da Galeria */
        .gallery-title {
            font-size: 1.5rem;
            font-weight: bold;
            color: #333;
            margin: 2rem 0 1rem;
        }

        /* Galeria de Imagens */
        .image-gallery {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            margin-bottom: 2rem;
        }

        .gallery-image {
            width: 150px;
            height: 100px;
            background-color: #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .gallery-image:hover {
            background-color: #ccc;
            transform: scale(1.05);
        }

        /* Espaço extra */
        .spacer {
            margin-bottom: 2rem;
        }

        /* Reset Básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        } 

        /* Header */
        header {
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 25px;
        }

        header a {
            text-decoration: none;
            color: #333;
            transition: color 0.3s ease;
        }

        header a:hover {
            color: #666;
        }

        header button {
            padding: 10px 20px;
            background-color: #414241;
            color: white;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        header button:hover {
            background-color: #333;
        }

        /* Seção de Contato */
        .contact-container {
            text-align: center;
            padding: 2rem;
        }

        .contact-container h2 {
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        .contact-container form {
            max-width: 500px;
            margin: 0 auto;
        }

        .contact-container input,
        .contact-container textarea {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-container button {
            padding: 0.8rem 1.5rem;
            background-color: #444;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
            transition: background-color 0.3s ease;
        }

        .contact-container button:hover {
            background-color: #333;
        }

        /* Footer */
        footer {
            background-color: #f9f9f9;
            padding: 2rem 10%;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            border-top: 1px solid #ddd;
        }

        footer h4 {
            margin-bottom: 1rem;
            font-size: 1rem;
        }

        footer a,
        footer p {
            display: block;
            margin-bottom: 0.5rem;
            color: #444;
            font-size: 0.9rem;
            text-decoration: none;
        }

        footer a:hover {
            color: #000;
        }

        .social-icons {
            display: flex;
            gap: 0.8rem;
            margin-top: 1rem;
        }

        .social-icons i {
            font-size: 1.2rem;
            cursor: pointer;
        }

        .copyright {
            text-align: center;
            margin-top: 1rem;
            font-size: 0.8rem;
            color: #888;
            width: 100%;
        }

        

</style>
