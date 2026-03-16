<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card com Habilidades</title>
    <style>
        /* Variáveis CSS */
        :root {
            --cor-html: #e34c26;
            --cor-css: #2965f1;
            --cor-js: #f0db4f;
            --cor-texto-badge: #000;
            --cor-hover-html: #c23d1a;
            --cor-hover-css: #1a54d9;
            --cor-hover-js: #d8c12e;
            --raio-borda: 16px;
            --transicao: 0.3s ease;
        }

        /* Estilo base do card (exemplo para contexto) */
        .card {
            width: 300px;
            padding: 2rem;
            border: 1px solid #eee;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin: 2rem;
        }

        /* Estilo da lista de habilidades */
        .habilidades-lista {
            list-style: none;
            padding: 0;
            margin: 1rem 0 0;
        }

        .habilidades-lista li {
            margin: 0.5rem 0;
        }

        /* Estilo dos badges */
        .badge {
            display: inline-block;
            padding: 0.4rem 1rem;
            border-radius: var(--raio-borda);
            color: var(--cor-texto-badge);
            font-weight: 500;
            transition: background-color var(--transicao);
        }

        .badge-html {
            background-color: var(--cor-html);
        }

        .badge-css {
            background-color: var(--cor-css);
        }

        .badge-js {
            background-color: var(--cor-js);
        }

        /* Efeito hover */
        .badge-html:hover {
            background-color: var(--cor-hover-html);
        }

        .badge-css:hover {
            background-color: var(--cor-hover-css);
        }

        .badge-js:hover {
            background-color: var(--cor-hover-js);
        }
    </style>
</head>
<body>
    <div class="card">
        <h2>Minhas Habilidades</h2>
        <ul class="habilidades-lista">
            <li><span class="badge badge-html">HTML</span></li>
            <li><span class="badge badge-css">CSS</span></li>
            <li><span class="badge badge-js">JavaScript</span></li>
        </ul>
    </div>
</body>
</html>
