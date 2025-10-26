# FORMUL-RIO-DADOS-PESSOAS-E-ACADEMICOS
MEU 1º SITE
TABELA DE DADOS ACADEMICOS
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela de Dados Académicos</title>
    <style>
        /* Estilos CSS simples para a tabela */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .academic-table {
            width: 100%; /* Ocupa toda a largura disponível */
            border-collapse: collapse; /* Remove o espaço duplo entre bordas */
            margin-top: 20px;
        }
        .academic-table th, .academic-table td {
            border: 1px solid #999; /* Borda simples */
            padding: 10px;
            text-align: left;
        }
        /* Estilo para o cabeçalho da tabela */
        .academic-table th {
            background-color: #f2f2f2;
            color: #333;
            font-weight: bold;
            text-align: center;
        }
        /* Estilo para a linha do nome, para destaque */
        .person-name {
            background-color: #e6e6ff; /* Cor clara para o nome da pessoa */
            font-weight: bold;
            text-align: center;
        }
    </style>
</head>
<body>

    <h2>Tabela de dados Académicos </h2>

    <table class="academic-table">
        <thead>
            <tr>
                <th colspan="3">Informações Académicas </th>
            </tr>
            <tr>
                <th>Nome Completo</th>
                <th>Curso</th>
                <th>Instituição</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="person-name">Dumilde Cabingano</td>
                <td>Informática e Gestão</td>
                <td>Instituto Médio Comercial de Luanda</td>
            </tr>
            <tr>
                <td class="person-name">Arlindo Campos</td>
                <td>Tecnico de Informática e Gestão </td>
                <td>Instituto Médio Comercial de Luanda</td>

            </tr>
            
            <tr>
                <td class="person-name">Pedro Finda</td>
                <td>Técnico de Informática e Gestão</td>
                <td>Instituto Médio Comercial de Luanda</td>
            </tr>
            <tr>
            </tr>
        </tbody>
    </table>

</body>
</html>
