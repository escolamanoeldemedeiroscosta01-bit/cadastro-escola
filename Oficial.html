<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EMEB Manoel de Medeiros Costa - Sistema de Gestão</title>
    <!-- FontAwesome para Ícones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-blue: #007bc4;
            --dark-blue: #005a93;
            --accent-red: #d32f2f;
            --hover-red: #b71c1c;
            --bg-gray: #f4f7f6;
            --text-dark: #2c3e50;
            --border-color: #cbd5e1;
            --success-green: #2e7d32;
            --warning-orange: #ed6c02;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-gray);
            color: var(--text-dark);
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        .header-wrapper {
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header {
            background: linear-gradient(135deg, var(--primary-blue), var(--dark-blue));
            color: white;
            padding: 15px 20px;
        }

        .header-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .header-textos {
            flex: 1;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 4px;
        }

        header h1 {
            font-size: 1.8rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }

        .direcao-texto {
            font-size: 0.95rem;
            font-weight: 500;
            background-color: rgba(255, 255, 255, 0.15);
            padding: 2px 12px;
            border-radius: 20px;
            letter-spacing: 0.5px;
        }

        header p {
            font-size: 0.9rem;
            font-weight: 300;
            opacity: 0.9;
        }

        nav {
            background-color: white;
            border-bottom: 2px solid #e2e8f0;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            position: relative;
        }

        .nav-btn {
            background: none;
            border: none;
            padding: 16px 20px;
            font-size: 0.95rem;
            font-weight: 600;
            color: var(--text-dark);
            cursor: pointer;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            gap: 8px;
            border-bottom: 4px solid transparent;
        }

        .nav-btn:hover {
            color: var(--primary-blue);
            background-color: #f8fafc;
        }

        .nav-btn.active {
            color: var(--primary-blue);
            border-bottom-color: var(--accent-red);
            background-color: #f1f5f9;
        }

        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: white;
            min-width: 240px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.15);
            z-index: 1001;
            border-radius: 0 0 6px 6px;
            border-top: 2px solid var(--primary-blue);
            left: 0;
        }

        .dropdown-content button {
            color: var(--text-dark);
            padding: 12px 16px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            width: 100%;
            background: none;
            border: none;
            text-align: left;
            cursor: pointer;
            font-size: 0.9rem;
            font-weight: 500;
            transition: background 0.2s;
        }

        .dropdown-content button:hover {
            background-color: #f1f5f9;
            color: var(--primary-blue);
        }

        .dropdown.active .dropdown-content {
            display: block;
        }

        main {
            max-width: 1200px;
            width: 100%;
            margin: 25px auto;
            padding: 0 20px;
            flex: 1;
        }

        .tab-content {
            display: none;
            animation: fadeIn 0.3s ease-in-out;
        }

        .tab-content.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(5px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .dashboard-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .stat-card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            border-left: 5px solid var(--primary-blue);
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .stat-card.red { border-left-color: var(--accent-red); }
        .stat-card.green { border-left-color: var(--success-green); }
        .stat-card.orange { border-left-color: var(--warning-orange); }

        .stat-info h3 {
            font-size: 0.85rem;
            color: #64748b;
            text-transform: uppercase;
            margin-bottom: 5px;
        }

        .stat-info .number {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--text-dark);
        }

        .stat-icon {
            font-size: 2rem;
            opacity: 0.2;
        }

        .panel {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            margin-bottom: 25px;
        }

        .panel-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #e2e8f0;
            flex-wrap: wrap;
            gap: 10px;
        }

        .panel-title {
            font-size: 1.3rem;
            color: var(--primary-blue);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 18px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 6px;
        }

        .form-group.full-width {
            grid-column: 1 / -1;
        }

        label {
            font-size: 0.9rem;
            font-weight: 600;
            color: #475569;
        }

        input, select, textarea {
            padding: 10px 12px;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            font-size: 0.95rem;
            outline: none;
            transition: border-color 0.2s;
        }

        input:focus, select:focus, textarea:focus {
            border-color: var(--primary-blue);
            box-shadow: 0 0 0 3px rgba(0, 123, 196, 0.15);
        }

        .photo-upload-container {
            display: flex;
            align-items: center;
            gap: 15px;
            background: #f8fafc;
            padding: 12px;
            border: 1px dashed var(--border-color);
            border-radius: 6px;
        }

        .photo-preview {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid var(--primary-blue);
            background-color: #e2e8f0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #94a3b8;
            font-size: 1.2rem;
            flex-shrink: 0;
            overflow: hidden;
        }

        .photo-preview img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .table-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            object-fit: cover;
            border: 1px solid #cbd5e1;
            display: inline-block;
            vertical-align: middle;
            margin-right: 8px;
            background-color: #e2e8f0;
            text-align: center;
            line-height: 40px;
            font-size: 0.9rem;
            color: #64748b;
        }

        .btn-submit {
            background-color: var(--accent-red);
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.2s;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            margin-top: 10px;
        }

        .btn-submit:hover {
            background-color: var(--hover-red);
        }

        .export-buttons {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .btn-print {
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 8px 14px;
            font-size: 0.85rem;
            font-weight: 600;
            border-radius: 6px;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            transition: background 0.2s;
        }

        .btn-print:hover {
            background-color: var(--dark-blue);
        }

        .btn-excel {
            background-color: var(--success-green);
            color: white;
            border: none;
            padding: 8px 14px;
            font-size: 0.85rem;
            font-weight: 600;
            border-radius: 6px;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            transition: background 0.2s;
        }

        .btn-excel:hover {
            background-color: #1b5e20;
        }

        .filters-container {
            display: flex;
            gap: 15px;
            margin-bottom: 20px;
            flex-wrap: wrap;
            background-color: #f8fafc;
            padding: 15px;
            border-radius: 6px;
            border: 1px solid #e2e8f0;
        }

        .filter-item {
            flex: 1;
            min-width: 180px;
        }

        .table-responsive {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            font-size: 0.9rem;
        }

        th {
            background-color: #f1f5f9;
            color: #334155;
            padding: 12px;
            font-weight: 600;
            border-bottom: 2px solid #cbd5e1;
        }

        td {
            padding: 12px;
            border-bottom: 1px solid #e2e8f0;
            vertical-align: middle;
        }

        tbody tr:hover {
            background-color: #f8fafc;
        }

        .badge {
            padding: 5px 12px;
            border-radius: 12px;
            font-size: 0.75rem;
            font-weight: bold;
            display: inline-block;
            text-transform: uppercase;
            cursor: pointer;
            transition: opacity 0.2s, transform 0.1s;
        }

        .badge:hover {
            opacity: 0.8;
            transform: scale(1.05);
        }

        .badge-matriculado, .badge-ativo {
            background-color: #dcfce7;
            color: #15803d;
        }

        .badge-transferido, .badge-licenca {
            background-color: #fef9c3;
            color: #a16207;
        }

        .badge-desistencia, .badge-desligado, .badge-concluido {
            background-color: #fee2e2;
            color: #b91c1c;
        }

        .action-btn {
            background: none;
            border: none;
            cursor: pointer;
            padding: 4px 8px;
            border-radius: 4px;
            color: #64748b;
            transition: color 0.2s;
        }

        .action-btn:hover {
            color: var(--primary-blue);
            background-color: #f1f5f9;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: white;
            border-top: 1px solid #e2e8f0;
            font-size: 0.85rem;
            color: #64748b;
            margin-top: auto;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 2000;
            align-items: center;
            justify-content: center;
        }

        .modal.active {
            display: flex;
        }

        .modal-content {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            width: 90%;
            max-width: 450px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            max-height: 90vh;
            overflow-y: auto;
        }

        .modal-header {
            font-weight: bold;
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: var(--primary-blue);
        }

        .modal-footer {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
            margin-top: 20px;
        }

        /* CONFIGURAÇÃO DE IMPRESSÃO: OCULTA O CABEÇALHO, MENU E BOTÕES DO SITE */
        @media print {
            .header-wrapper, nav, .filters-container, .export-buttons, .action-col, .action-btn, footer, .btn-print, .btn-excel {
                display: none !important;
            }
            body {
                background-color: white;
                color: black;
            }
            .panel {
                box-shadow: none;
                border: none;
                padding: 0;
            }
            main {
                margin: 0;
                padding: 0;
                max-width: 100%;
            }
            .tab-content {
                display: block !important;
            }
        }
    </style>
    <!-- SheetJS para exportação real em Excel (.xlsx) -->
    <script src="https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js"></script>
</head>
<body>

    <div class="header-wrapper">
        <header>
            <div class="header-container">
                <div class="header-textos">
                    <h1>EMEB Manoel de Medeiros Costa</h1>
                    <div class="direcao-texto">Direção: Valdineide Alves da Silva</div>
                    <p>São Bento, Maragogi / AL - Ensino Fundamental (1º ao 9º Ano)</p>
                </div>
            </div>
        </header>

        <nav>
            <div class="nav-container">
                <button class="nav-btn active" onclick="switchTab('dashboard')"><i class="fa-solid fa-chart-pie"></i> Painel Geral</button>
                
                <!-- DROPDOWN DE CADASTRO -->
                <div class="dropdown" id="dropdownCadastro">
                    <button class="nav-btn" onclick="toggleDropdown('dropdownCadastro', event)"><i class="fa-solid fa-user-plus"></i> Cadastro <i class="fa-solid fa-caret-down"></i></button>
                    <div class="dropdown-content">
                        <button onclick="switchTab('cad-aluno'); fecharTodosDropdowns();"><i class="fa-solid fa-graduation-cap"></i> Cadastrar Aluno Novo</button>
                        <button onclick="switchTab('cad-arquivo'); fecharTodosDropdowns();"><i class="fa-solid fa-box-archive"></i> Cadastrar Acervo Arquivado</button>
                        <button onclick="switchTab('cad-funcionario'); fecharTodosDropdowns();"><i class="fa-solid fa-user-tie"></i> Cadastrar Funcionário</button>
                    </div>
                </div>

                <!-- DROPDOWN DE LISTA -->
                <div class="dropdown" id="dropdownLista">
                    <button class="nav-btn" onclick="toggleDropdown('dropdownLista', event)"><i class="fa-solid fa-list"></i> Lista <i class="fa-solid fa-caret-down"></i></button>
                    <div class="dropdown-content">
                        <button onclick="switchTab('lista-alunos'); fecharTodosDropdowns();"><i class="fa-solid fa-users"></i> Lista de Alunos</button>
                        <button onclick="switchTab('lista-funcionarios'); fecharTodosDropdowns();"><i class="fa-solid fa-id-card-clip"></i> Lista de Funcionários</button>
                    </div>
                </div>

                <!-- DROPDOWN DE RELATÓRIO -->
                <div class="dropdown" id="dropdownRelatorio">
                    <button class="nav-btn" onclick="toggleDropdown('dropdownRelatorio', event)"><i class="fa-solid fa-file-lines"></i> Relatório <i class="fa-solid fa-caret-down"></i></button>
                    <div class="dropdown-content">
                        <button onclick="switchTab('relatorio-aluno'); fecharTodosDropdowns();"><i class="fa-solid fa-user-graduate"></i> Relatório por Aluno</button>
                        <button onclick="switchTab('relatorio-funcionario'); fecharTodosDropdowns();"><i class="fa-solid fa-briefcase"></i> Relatório por Funcionário</button>
                    </div>
                </div>

                <!-- BOTÃO DE MIGRAÇÃO DE TURMAS -->
                <button class="nav-btn" onclick="switchTab('migracao-turmas')"><i class="fa-solid fa-arrows-split-up-and-left"></i> Migração de Turmas</button>
            </div>
        </nav>
    </div>

    <main>

        <!-- ABA 1: PAINEL GERAL / DASHBOARD -->
        <section id="dashboard" class="tab-content active">
            <div class="dashboard-grid">
                <div class="stat-card">
                    <div class="stat-info">
                        <h3>Alunos Matriculados</h3>
                        <div class="number" id="stat-alunos-ativos">0</div>
                    </div>
                    <i class="fa-solid fa-user-graduate stat-icon" style="color: var(--primary-blue);"></i>
                </div>
                <div class="stat-card red">
                    <div class="stat-info">
                        <h3>Funcionários Ativos</h3>
                        <div class="number" id="stat-func-ativos">0</div>
                    </div>
                    <i class="fa-solid fa-briefcase stat-icon" style="color: var(--accent-red);"></i>
                </div>
                <div class="stat-card orange">
                    <div class="stat-info">
                        <h3>Transferidos / Saídas</h3>
                        <div class="number" id="stat-alunos-saida">0</div>
                    </div>
                    <i class="fa-solid fa-right-from-bracket stat-icon" style="color: var(--warning-orange);"></i>
                </div>
                <div class="stat-card green">
                    <div class="stat-info">
                        <h3>Total Cadastros</h3>
                        <div class="number" id="stat-total-geral">0</div>
                    </div>
                    <i class="fa-solid fa-folder-open stat-icon" style="color: var(--success-green);"></i>
                </div>
            </div>

            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-circle-info"></i> Resumo por Série Escolar</h2>
                </div>
                <div class="table-responsive">
                    <table>
                        <thead>
                            <tr>
                                <th>Ano / Série</th>
                                <th>Matriculados</th>
                                <th>Transferidos</th>
                                <th>Desistências</th>
                                <th>Total</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-resumo-series">
                            <!-- Preenchido via JavaScript -->
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ABA: CADASTRO DE ALUNO NOVO -->
        <section id="cad-aluno" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-graduation-cap"></i> Cadastro de Aluno Novo (Ativo)</h2>
                </div>
                <form id="formAluno" onsubmit="salvarAluno(event, false)">
                    <div class="form-grid">
                        <div class="form-group full-width">
                            <label>Foto do Aluno</label>
                            <div class="photo-upload-container">
                                <div class="photo-preview" id="alunoPhotoPreview">
                                    <i class="fa-solid fa-user"></i>
                                </div>
                                <div style="flex: 1;">
                                    <input type="file" id="alunoFoto" accept="image/*" onchange="previewFoto(event, 'alunoPhotoPreview')">
                                    <small style="color: #64748b; display: block; margin-top: 4px;">Selecione uma imagem (PNG, JPG)</small>
                                </div>
                            </div>
                        </div>

                        <div class="form-group full-width">
                            <label for="alunoNome">Nome Completo do Aluno *</label>
                            <input type="text" id="alunoNome" required placeholder="Digite o nome completo do aluno">
                        </div>

                        <div class="form-group">
                            <label for="alunoDataNasc">Data de Nascimento *</label>
                            <input type="date" id="alunoDataNasc" required>
                        </div>

                        <div class="form-group">
                            <label for="alunoEstadoNasc">Estado de Nascimento *</label>
                            <select id="alunoEstadoNasc" required onchange="carregarCidades(this.value, 'alunoEstadoNasc', 'alunoCidadeNasc')">
                                <option value="">Carregando estados...</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="alunoCidadeNasc">Cidade de Nascimento *</label>
                            <select id="alunoCidadeNasc" required disabled>
                                <option value="">Selecione o Estado primeiro</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="alunoCpf">CPF do Aluno</label>
                            <input type="text" id="alunoCpf" class="cpf-mask" placeholder="000.000.000-00 (Opcional)">
                        </div>

                        <div class="form-group">
                            <label for="alunoAnoLetivo">Ano Letivo (Ex: 2026) *</label>
                            <input type="text" id="alunoAnoLetivo" required placeholder="Ex: 2026">
                        </div>

                        <div class="form-group">
                            <label for="alunoAno">Série *</label>
                            <select id="alunoAno" required>
                                <option value="">Selecione a Série</option>
                                <option value="1º Ano">1º Ano</option>
                                <option value="2º Ano">2º Ano</option>
                                <option value="3º Ano">3º Ano</option>
                                <option value="4º Ano">4º Ano</option>
                                <option value="5º Ano">5º Ano</option>
                                <option value="6º Ano">6º Ano</option>
                                <option value="7º Ano">7º Ano</option>
                                <option value="8º Ano">8º Ano</option>
                                <option value="9º Ano">9º Ano</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="alunoTurma">Turma *</label>
                            <select id="alunoTurma" required>
                                <option value="">Selecione a Turma</option>
                                <option value="A">Turma A</option>
                                <option value="B">Turma B</option>
                                <option value="C">Turma C</option>
                                <option value="D">Turma D</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="nomeMae">Nome da Mãe *</label>
                            <input type="text" id="nomeMae" required placeholder="Nome da mãe ou responsável">
                        </div>

                        <div class="form-group">
                            <label for="telMae">Telefone da Mãe</label>
                            <input type="tel" id="telMae" class="phone-mask" placeholder="(82) 9XXXX-XXXX">
                        </div>

                        <div class="form-group">
                            <label for="nomePai">Nome do Pai</label>
                            <input type="text" id="nomePai" placeholder="Nome do pai (opcional)">
                        </div>

                        <div class="form-group">
                            <label for="telPai">Telefone do Pai</label>
                            <input type="tel" id="telPai" class="phone-mask" placeholder="(82) 9XXXX-XXXX">
                        </div>

                        <div class="form-group full-width">
                            <label for="alunoEndereco">Endereço Residencial *</label>
                            <input type="text" id="alunoEndereco" required placeholder="Rua, Número, Bairro, Povoado / Referência">
                        </div>
                    </div>

                    <button type="submit" class="btn-submit"><i class="fa-solid fa-save"></i> Salvar Aluno Novo</button>
                </form>
            </div>
        </section>

        <!-- ABA: CADASTRO DE ACERVO ARQUIVADO -->
        <section id="cad-arquivo" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-box-archive"></i> Cadastro de Acervo Arquivado (Papel Antigo)</h2>
                </div>
                <form id="formArquivo" onsubmit="salvarAluno(event, true)">
                    <div class="form-grid">
                        <div class="form-group full-width">
                            <label>Foto do Aluno (Opcional para acervo antigo)</label>
                            <div class="photo-upload-container">
                                <div class="photo-preview" id="arquivoPhotoPreview">
                                    <i class="fa-solid fa-user"></i>
                                </div>
                                <div style="flex: 1;">
                                    <input type="file" id="arquivoFoto" accept="image/*" onchange="previewFoto(event, 'arquivoPhotoPreview')">
                                    <small style="color: #64748b; display: block; margin-top: 4px;">Selecione uma imagem (PNG, JPG)</small>
                                </div>
                            </div>
                        </div>

                        <div class="form-group full-width">
                            <label for="arqNome">Nome Completo do Aluno *</label>
                            <input type="text" id="arqNome" required placeholder="Digite o nome completo do aluno antigo">
                        </div>

                        <div class="form-group">
                            <label for="arqDataNasc">Data de Nascimento *</label>
                            <input type="date" id="arqDataNasc" required>
                        </div>

                        <div class="form-group">
                            <label for="arqEstadoNasc">Estado de Nascimento *</label>
                            <select id="arqEstadoNasc" required onchange="carregarCidades(this.value, 'arqEstadoNasc', 'arqCidadeNasc')">
                                <option value="">Carregando estados...</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="arqCidadeNasc">Cidade de Nascimento *</label>
                            <select id="arqCidadeNasc" required disabled>
                                <option value="">Selecione o Estado primeiro</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="arqCpf">CPF do Aluno</label>
                            <input type="text" id="arqCpf" class="cpf-mask" placeholder="000.000.000-00 (Opcional)">
                        </div>

                        <div class="form-group">
                            <label for="arqAnoLetivo">Ano Letivo de Referência (Ex: 2023) *</label>
                            <input type="text" id="arqAnoLetivo" required placeholder="Ex: 2023">
                        </div>

                        <div class="form-group">
                            <label for="arqAno">Série *</label>
                            <select id="arqAno" required>
                                <option value="">Selecione a Série</option>
                                <option value="1º Ano">1º Ano</option>
                                <option value="2º Ano">2º Ano</option>
                                <option value="3º Ano">3º Ano</option>
                                <option value="4º Ano">4º Ano</option>
                                <option value="5º Ano">5º Ano</option>
                                <option value="6º Ano">6º Ano</option>
                                <option value="7º Ano">7º Ano</option>
                                <option value="8º Ano">8º Ano</option>
                                <option value="9º Ano">9º Ano</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="arqTurma">Turma *</label>
                            <select id="arqTurma" required>
                                <option value="">Selecione a Turma</option>
                                <option value="A">Turma A</option>
                                <option value="B">Turma B</option>
                                <option value="C">Turma C</option>
                                <option value="D">Turma D</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="arqDataEntrada">Data em que Entrou na Escola *</label>
                            <input type="date" id="arqDataEntrada" required>
                        </div>

                        <div class="form-group">
                            <label for="arqDataSaida">Data em que Saiu da Escola *</label>
                            <input type="date" id="arqDataSaida" required>
                        </div>

                        <div class="form-group">
                            <label for="arqStatus">Status do Arquivo *</label>
                            <select id="arqStatus" required>
                                <option value="">Selecione o Status</option>
                                <option value="Transferido">Transferido</option>
                                <option value="Concluído">Concluído / Formado</option>
                                <option value="Desistência">Desistência</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="arqNomeMae">Nome da Mãe *</label>
                            <input type="text" id="arqNomeMae" required placeholder="Nome da mãe ou responsável">
                        </div>

                        <div class="form-group">
                            <label for="arqTelMae">Telefone da Mãe</label>
                            <input type="tel" id="arqTelMae" class="phone-mask" placeholder="(82) 9XXXX-XXXX">
                        </div>

                        <div class="form-group">
                            <label for="arqNomePai">Nome do Pai</label>
                            <input type="text" id="arqNomePai" placeholder="Nome do pai (opcional)">
                        </div>

                        <div class="form-group">
                            <label for="arqTelPai">Telefone do Pai</label>
                            <input type="tel" id="arqTelPai" class="phone-mask" placeholder="(82) 9XXXX-XXXX">
                        </div>

                        <div class="form-group full-width">
                            <label for="arqEndereco">Endereço Residencial *</label>
                            <input type="text" id="arqEndereco" required placeholder="Rua, Número, Bairro, Povoado / Referência">
                        </div>
                    </div>

                    <button type="submit" class="btn-submit"><i class="fa-solid fa-box-archive"></i> Salvar Acervo Arquivado</button>
                </form>
            </div>
        </section>

        <!-- ABA: CADASTRO DE FUNCIONÁRIO -->
        <section id="cad-funcionario" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-user-tie"></i> Cadastro de Funcionário</h2>
                </div>
                <form id="formFuncionario" onsubmit="salvarFuncionario(event)">
                    <div class="form-grid">
                        <div class="form-group full-width">
                            <label>Foto do Funcionário</label>
                            <div class="photo-upload-container">
                                <div class="photo-preview" id="funcPhotoPreview">
                                    <i class="fa-solid fa-user-tie"></i>
                                </div>
                                <div style="flex: 1;">
                                    <input type="file" id="funcFoto" accept="image/*" onchange="previewFoto(event, 'funcPhotoPreview')">
                                    <small style="color: #64748b; display: block; margin-top: 4px;">Selecione uma imagem (PNG, JPG)</small>
                                </div>
                            </div>
                        </div>

                        <div class="form-group full-width">
                            <label for="funcNome">Nome Completo *</label>
                            <input type="text" id="funcNome" required placeholder="Digite o nome do funcionário">
                        </div>

                        <div class="form-group">
                            <label for="funcCargo">Cargo / Função *</label>
                            <select id="funcCargo" required onchange="verificarCargoProfessor()">
                                <option value="">Selecione o Cargo</option>
                                <option value="Professor">Professor(a)</option>
                                <option value="Auxiliar de Sala">Auxiliar de Sala</option>
                                <option value="Merendeiro">Merendeiro(a)</option>
                                <option value="Porteiro">Porteiro(a)</option>
                                <option value="Serviços Gerais">Serviços Gerais</option>
                                <option value="Coordenador">Coordenador(a)</option>
                                <option value="Diretor">Diretor(a)</option>
                                <option value="Motorista">Motorista</option>
                            </select>
                        </div>

                        <div class="form-group" id="grupoAreaAtuacao" style="display: none;">
                            <label for="funcAreaAtuacao">Área de Atuação *</label>
                            <select id="funcAreaAtuacao">
                                <option value="">Selecione a Área</option>
                                <option value="Pedagogia">Pedagogia</option>
                                <option value="Computação">Computação</option>
                                <option value="Educação Física">Educação Física</option>
                                <option value="Matemática">Matemática</option>
                                <option value="Letras / Língua Portuguesa">Letras / Língua Portuguesa</option>
                                <option value="Ciências">Ciências</option>
                                <option value="História">História</option>
                                <option value="Geografia">Geografia</option>
                                <option value="Artes">Artes</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="funcTelefone">Telefone / WhatsApp *</label>
                            <input type="tel" id="funcTelefone" class="phone-mask" required placeholder="(82) 9XXXX-XXXX">
                        </div>

                        <div class="form-group">
                            <label for="funcCargaHoraria">Carga Horária Semanal *</label>
                            <select id="funcCargaHoraria" required>
                                <option value="">Selecione a Carga Horária</option>
                                <option value="20h">20 Horas Semanais</option>
                                <option value="25h">25 Horas Semanais</option>
                                <option value="30h">30 Horas Semanais</option>
                                <option value="40h">40 Horas Semanais</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="funcVinculo">Vínculo Empregatício *</label>
                            <select id="funcVinculo" required>
                                <option value="">Selecione o Vínculo</option>
                                <option value="Efetivo">Efetivo / Concursado</option>
                                <option value="Contratado">Contratado / Temporário</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="funcDataAdmissao">Data de Admissão na Escola *</label>
                            <input type="date" id="funcDataAdmissao" required>
                        </div>

                        <div class="form-group">
                            <label for="funcEstado">Estado (UF) *</label>
                            <select id="funcEstado" required onchange="carregarCidades(this.value, 'funcEstado', 'funcCidade')">
                                <option value="">Carregando estados...</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="funcCidade">Cidade *</label>
                            <select id="funcCidade" required disabled>
                                <option value="">Selecione o Estado primeiro</option>
                            </select>
                        </div>

                        <div class="form-group">
                            <label for="funcBairro">Bairro *</label>
                            <input type="text" id="funcBairro" required placeholder="Digite o bairro">
                        </div>

                        <div class="form-group full-width">
                            <label for="funcRuaNum">Rua e Número *</label>
                            <input type="text" id="funcRuaNum" required placeholder="Ex: Rua Principal, nº 123">
                        </div>
                    </div>

                    <button type="submit" class="btn-submit"><i class="fa-solid fa-save"></i> Salvar Funcionário</button>
                </form>
            </div>
        </section>

        <!-- ABA: LISTA DE ALUNOS -->
        <section id="lista-alunos" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-graduation-cap"></i> Relação de Alunos</h2>
                    <div class="export-buttons">
                        <button type="button" class="btn-excel" onclick="exportarParaExcel('lista-alunos-table', 'relacao_alunos.xlsx', 'Alunos')">
                            <i class="fa-solid fa-file-excel"></i> Baixar Planilha (Excel)
                        </button>
                        <button type="button" class="btn-print" onclick="imprimirTabela('lista-alunos-table', 'Relação Oficial de Alunos')">
                            <i class="fa-solid fa-file-pdf"></i> Baixar PDF / Imprimir
                        </button>
                    </div>
                </div>

                <div class="filters-container">
                    <div class="filter-item">
                        <label for="filterAnoLetivo">Filtrar por Ano Letivo:</label>
                        <input type="text" id="filterAnoLetivo" placeholder="Ex: 2026" oninput="renderizarAlunos()">
                    </div>

                    <div class="filter-item">
                        <label for="filterAno">Filtrar por Série:</label>
                        <select id="filterAno" onchange="renderizarAlunos()">
                            <option value="">Todas as Séries</option>
                            <option value="1º Ano">1º Ano</option>
                            <option value="2º Ano">2º Ano</option>
                            <option value="3º Ano">3º Ano</option>
                            <option value="4º Ano">4º Ano</option>
                            <option value="5º Ano">5º Ano</option>
                            <option value="6º Ano">6º Ano</option>
                            <option value="7º Ano">7º Ano</option>
                            <option value="8º Ano">8º Ano</option>
                            <option value="9º Ano">9º Ano</option>
                        </select>
                    </div>

                    <div class="filter-item">
                        <label for="filterTurma">Filtrar por Turma:</label>
                        <select id="filterTurma" onchange="renderizarAlunos()">
                            <option value="">Todas as Turmas</option>
                            <option value="A">Turma A</option>
                            <option value="B">Turma B</option>
                            <option value="C">Turma C</option>
                            <option value="D">Turma D</option>
                        </select>
                    </div>

                    <div class="filter-item">
                        <label for="searchAluno">Buscar por Nome:</label>
                        <input type="text" id="searchAluno" placeholder="Digite o nome..." oninput="renderizarAlunos()">
                    </div>
                </div>

                <div class="table-responsive">
                    <table id="lista-alunos-table">
                        <thead>
                            <tr>
                                <th>Aluno / CPF</th>
                                <th>Data Nasc.</th>
                                <th>Naturalidade</th>
                                <th>Ano Letivo / Série / Turma</th>
                                <th>Período (Entrada / Saída)</th>
                                <th>Filiação / Responsável</th>
                                <th>Telefones</th>
                                <th>Endereço</th>
                                <th>Status</th>
                                <th class="action-col">Ações</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-alunos">
                            <!-- Preenchido por JS -->
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ABA: LISTA DE FUNCIONÁRIOS -->
        <section id="lista-funcionarios" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-user-tie"></i> Quadro de Funcionários</h2>
                    <div class="export-buttons">
                        <button type="button" class="btn-excel" onclick="exportarParaExcel('lista-funcionarios-table', 'relacao_funcionarios.xlsx', 'Funcionarios')">
                            <i class="fa-solid fa-file-excel"></i> Baixar Planilha (Excel)
                        </button>
                        <button type="button" class="btn-print" onclick="imprimirTabela('lista-funcionarios-table', 'Quadro Oficial de Funcionários e Colaboradores')">
                            <i class="fa-solid fa-file-pdf"></i> Baixar PDF / Imprimir
                        </button>
                    </div>
                </div>

                <div class="filters-container">
                    <div class="filter-item">
                        <label for="filterCargo">Filtrar por Cargo:</label>
                        <select id="filterCargo" onchange="renderizarFuncionarios()">
                            <option value="">Todos os Cargos</option>
                            <option value="Professor">Professor(a)</option>
                            <option value="Auxiliar de Sala">Auxiliar de Sala</option>
                            <option value="Merendeiro">Merendeiro(a)</option>
                            <option value="Porteiro">Porteiro(a)</option>
                            <option value="Serviços Gerais">Serviços Gerais</option>
                            <option value="Coordenador">Coordenador(a)</option>
                            <option value="Diretor">Diretor(a)</option>
                            <option value="Motorista">Motorista</option>
                        </select>
                    </div>

                    <div class="filter-item">
                        <label for="filterStatusFunc">Filtrar por Status:</label>
                        <select id="filterStatusFunc" onchange="renderizarFuncionarios()">
                            <option value="">Todos os Status</option>
                            <option value="Ativo">Ativo</option>
                            <option value="Licença">Licença</option>
                            <option value="Desligado">Desligado</option>
                        </select>
                    </div>

                    <div class="filter-item">
                        <label for="searchFunc">Buscar por Nome:</label>
                        <input type="text" id="searchFunc" placeholder="Digite o nome..." oninput="renderizarFuncionarios()">
                    </div>
                </div>

                <div class="table-responsive">
                    <table id="lista-funcionarios-table">
                        <thead>
                            <tr>
                                <th>Nome</th>
                                <th>Cargo / Área</th>
                                <th>Carga Horária</th>
                                <th>Vínculo</th>
                                <th>Admissão</th>
                                <th>Telefone</th>
                                <th>Endereço (Rua/Bairro/Cidade-UF)</th>
                                <th>Status</th>
                                <th class="action-col">Ações</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-funcionarios">
                            <!-- Preenchido por JS -->
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ABA: RELATÓRIO POR ALUNO -->
        <section id="relatorio-aluno" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-user-graduate"></i> Relatório Analítico por Aluno</h2>
                    <button type="button" class="btn-print" onclick="window.print()">
                        <i class="fa-solid fa-print"></i> Imprimir Relatório
                    </button>
                </div>
                <p style="margin-bottom: 20px; color: #64748b;">Selecione um aluno para visualizar sua ficha detalhada de informações escolares e cadastrais:</p>
                
                <div class="form-group" style="max-width: 400px; margin-bottom: 20px;">
                    <label for="selectRelatorioAluno">Escolher Aluno:</label>
                    <select id="selectRelatorioAluno" onchange="gerarRelatorioAlunoEspecifico(this.value)">
                        <option value="">Selecione um aluno...</option>
                    </select>
                </div>

                <div id="containerRelatorioAluno" style="border: 1px solid #cbd5e1; padding: 25px; border-radius: 8px; background: #fff;">
                    <p style="text-align: center; color: #94a3b8;">Nenhum aluno selecionado.</p>
                </div>
            </div>
        </section>

        <!-- ABA: RELATÓRIO POR FUNCIONÁRIO -->
        <section id="relatorio-funcionario" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-briefcase"></i> Relatório Analítico por Funcionário</h2>
                    <button type="button" class="btn-print" onclick="window.print()">
                        <i class="fa-solid fa-print"></i> Imprimir Relatório
                    </button>
                </div>
                <p style="margin-bottom: 20px; color: #64748b;">Selecione um funcionário para visualizar sua ficha detalhada de informações funcionais:</p>
                
                <div class="form-group" style="max-width: 400px; margin-bottom: 20px;">
                    <label for="selectRelatorioFunc">Escolher Funcionário:</label>
                    <select id="selectRelatorioFunc" onchange="gerarRelatorioFuncEspecifico(this.value)">
                        <option value="">Selecione um funcionário...</option>
                    </select>
                </div>

                <div id="containerRelatorioFunc" style="border: 1px solid #cbd5e1; padding: 25px; border-radius: 8px; background: #fff;">
                    <p style="text-align: center; color: #94a3b8;">Nenhum funcionário selecionado.</p>
                </div>
            </div>
        </section>

        <!-- ABA: MIGRAÇÃO E PROMOÇÃO DE TURMAS -->
        <section id="migracao-turmas" class="tab-content">
            <div class="panel">
                <div class="panel-header">
                    <h2 class="panel-title"><i class="fa-solid fa-arrows-split-up-and-left"></i> Migração e Promoção de Alunos em Lote</h2>
                </div>
                <p style="margin-bottom: 20px; color: #64748b;">Utilize esta ferramenta no final do ano letivo para promover os alunos de uma turma origem para a nova série/turma de destino em massa.</p>
                
                <div class="form-grid" style="background-color: #f8fafc; padding: 20px; border-radius: 8px; border: 1px solid #e2e8f0; margin-bottom: 20px;">
                    <div class="form-group">
                        <label for="origemAnoLetivo">Ano Letivo Origem *</label>
                        <input type="text" id="origemAnoLetivo" placeholder="Ex: 2025" oninput="atualizarListaPreviaMigracao()">
                    </div>

                    <div class="form-group">
                        <label for="origemAno">Série Atual (Origem) *</label>
                        <select id="origemAno" onchange="atualizarListaPreviaMigracao()">
                            <option value="">Selecione a Série</option>
                            <option value="1º Ano">1º Ano</option>
                            <option value="2º Ano">2º Ano</option>
                            <option value="3º Ano">3º Ano</option>
                            <option value="4º Ano">4º Ano</option>
                            <option value="5º Ano">5º Ano</option>
                            <option value="6º Ano">6º Ano</option>
                            <option value="7º Ano">7º Ano</option>
                            <option value="8º Ano">8º Ano</option>
                            <option value="9º Ano">9º Ano</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label for="origemTurma">Turma Atual (Origem) *</label>
                        <select id="origemTurma" onchange="atualizarListaPreviaMigracao()">
                            <option value="">Selecione a Turma</option>
                            <option value="A">Turma A</option>
                            <option value="B">Turma B</option>
                            <option value="C">Turma C</option>
                            <option value="D">Turma D</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label for="destinoAnoLetivo">Novo Ano Letivo Destino *</label>
                        <input type="text" id="destinoAnoLetivo" placeholder="Ex: 2026">
                    </div>

                    <div class="form-group">
                        <label for="destinoAno">Nova Série (Destino) *</label>
                        <select id="destinoAno">
                            <option value="">Selecione o Destino</option>
                            <option value="2º Ano">2º Ano</option>
                            <option value="3º Ano">3º Ano</option>
                            <option value="4º Ano">4º Ano</option>
                            <option value="5º Ano">5º Ano</option>
                            <option value="6º Ano">6º Ano</option>
                            <option value="7º Ano">7º Ano</option>
                            <option value="8º Ano">8º Ano</option>
                            <option value="9º Ano">9º Ano</option>
                            <option value="Concluído">Concluído (Fim do Fundamental)</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label for="destinoTurma">Nova Turma (Destino)</label>
                        <select id="destinoTurma">
                            <option value="A">Turma A</option>
                            <option value="B">Turma B</option>
                            <option value="C">Turma C</option>
                            <option value="D">Turma D</option>
                        </select>
                    </div>
                </div>

                <div style="margin-bottom: 20px;">
                    <h3 style="font-size: 1.1rem; margin-bottom: 10px; color: var(--text-dark);">Alunos encontrados nesta turma (<span id="contadorAlunosMigracao">0</span>):</h3>
                    <div class="table-responsive" style="max-height: 250px; overflow-y: auto;">
                        <table>
                            <thead>
                                <tr>
                                    <th>Nome do Aluno</th>
                                    <th>Status Atual</th>
                                    <th>Referência Atual</th>
                                </tr>
                            </thead>
                            <tbody id="tbody-previa-migracao">
                                <tr><td colspan="3" style="text-align:center; color: #94a3b8;">Preencha os filtros de origem acima.</td></tr>
                            </tbody>
                        </table>
                    </div>
                </div>

                <button type="button" class="btn-submit" onclick="executarMigracaoLote()">
                    <i class="fa-solid fa-check-double"></i> Executar Migração da Turma
                </button>
            </div>
        </section>

    </main>

    <!-- MODAL DE STATUS -->
    <div class="modal" id="statusModal">
        <div class="modal-content">
            <div class="modal-header">Alterar Status</div>
            <p id="modalItemNome" style="margin-bottom: 15px; font-weight: 500;"></p>
            <div class="form-group">
                <label for="modalStatusSelect">Selecione o novo Status:</label>
                <select id="modalStatusSelect"></select>
            </div>
            <div class="modal-footer">
                <button class="action-btn" onclick="fecharModalStatus()">Cancelar</button>
                <button class="btn-submit" style="padding: 6px 15px; margin-top:0;" onclick="confirmarAlteracaoStatus()">Salvar</button>
            </div>
        </div>
    </div>

    <!-- MODAL DE EDIÇÃO DE ALUNO -->
    <div class="modal" id="editAlunoModal">
        <div class="modal-content" style="max-width: 600px;">
            <div class="modal-header">Editar Cadastro de Aluno</div>
            <form id="formEditAluno" onsubmit="salvarEdicaoAluno(event)">
                <input type="hidden" id="editAlunoId">
                <div class="form-grid">
                    <div class="form-group full-width">
                        <label>Alterar Foto</label>
                        <div class="photo-upload-container">
                            <div class="photo-preview" id="editAlunoPhotoPreview">
                                <i class="fa-solid fa-user"></i>
                            </div>
                            <div style="flex: 1;">
                                <input type="file" id="editAlunoFoto" accept="image/*" onchange="previewFoto(event, 'editAlunoPhotoPreview')">
                            </div>
                        </div>
                    </div>
                    <div class="form-group full-width">
                        <label>Nome Completo do Aluno *</label>
                        <input type="text" id="editAlunoNome" required>
                    </div>
                    <div class="form-group">
                        <label>Data de Nascimento *</label>
                        <input type="date" id="editAlunoDataNasc" required>
                    </div>
                    <div class="form-group">
                        <label>CPF do Aluno</label>
                        <input type="text" id="editAlunoCpf" class="cpf-mask">
                    </div>
                    <div class="form-group">
                        <label>Ano Letivo *</label>
                        <input type="text" id="editAlunoAnoLetivo" required>
                    </div>
                    <div class="form-group">
                        <label>Ano / Série *</label>
                        <select id="editAlunoAno" required>
                            <option value="1º Ano">1º Ano</option>
                            <option value="2º Ano">2º Ano</option>
                            <option value="3º Ano">3º Ano</option>
                            <option value="4º Ano">4º Ano</option>
                            <option value="5º Ano">5º Ano</option>
                            <option value="6º Ano">6º Ano</option>
                            <option value="7º Ano">7º Ano</option>
                            <option value="8º Ano">8º Ano</option>
                            <option value="9º Ano">9º Ano</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Turma *</label>
                        <select id="editAlunoTurma" required>
                            <option value="A">Turma A</option>
                            <option value="B">Turma B</option>
                            <option value="C">Turma C</option>
                            <option value="D">Turma D</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Nome da Mãe *</label>
                        <input type="text" id="editNomeMae" required>
                    </div>
                    <div class="form-group">
                        <label>Telefone da Mãe</label>
                        <input type="tel" id="editTelMae" class="phone-mask">
                    </div>
                    <div class="form-group">
                        <label>Nome do Pai</label>
                        <input type="text" id="editNomePai">
                    </div>
                    <div class="form-group">
                        <label>Telefone do Pai</label>
                        <input type="tel" id="editTelPai" class="phone-mask">
                    </div>
                    <div class="form-group full-width">
                        <label>Endereço Residencial *</label>
                        <input type="text" id="editAlunoEndereco" required>
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="action-btn" onclick="fecharModalEdicaoAluno()">Cancelar</button>
                    <button type="submit" class="btn-submit" style="padding: 6px 15px; margin-top:0;">Salvar Alterações</button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL DE EDIÇÃO DE FUNCIONÁRIO -->
    <div class="modal" id="editFuncModal">
        <div class="modal-content" style="max-width: 600px;">
            <div class="modal-header">Editar Cadastro de Funcionário</div>
            <form id="formEditFunc" onsubmit="salvarEdicaoFuncionario(event)">
                <input type="hidden" id="editFuncId">
                <div class="form-grid">
                    <div class="form-group full-width">
                        <label>Alterar Foto</label>
                        <div class="photo-upload-container">
                            <div class="photo-preview" id="editFuncPhotoPreview">
                                <i class="fa-solid fa-user-tie"></i>
                            </div>
                            <div style="flex: 1;">
                                <input type="file" id="editFuncFoto" accept="image/*" onchange="previewFoto(event, 'editFuncPhotoPreview')">
                            </div>
                        </div>
                    </div>
                    <div class="form-group full-width">
                        <label>Nome Completo *</label>
                        <input type="text" id="editFuncNome" required>
                    </div>
                    <div class="form-group">
                        <label>Cargo / Função *</label>
                        <select id="editFuncCargo" required onchange="verificarCargoProfessorEdicao()">
                            <option value="Professor">Professor(a)</option>
                            <option value="Auxiliar de Sala">Auxiliar de Sala</option>
                            <option value="Merendeiro">Merendeiro(a)</option>
                            <option value="Porteiro">Porteiro(a)</option>
                            <option value="Serviços Gerais">Serviços Gerais</option>
                            <option value="Coordenador">Coordenador(a)</option>
                            <option value="Diretor">Diretor(a)</option>
                            <option value="Motorista">Motorista</option>
                        </select>
                    </div>
                    <div class="form-group" id="grupoEditAreaAtuacao" style="display: none;">
                        <label>Área de Atuação *</label>
                        <select id="editFuncAreaAtuacao">
                            <option value="Pedagogia">Pedagogia</option>
                            <option value="Computação">Computação</option>
                            <option value="Educação Física">Educação Física</option>
                            <option value="Matemática">Matemática</option>
                            <option value="Letras / Língua Portuguesa">Letras / Língua Portuguesa</option>
                            <option value="Ciências">Ciências</option>
                            <option value="História">História</option>
                            <option value="Geografia">Geografia</option>
                            <option value="Artes">Artes</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Telefone / WhatsApp *</label>
                        <input type="tel" id="editFuncTelefone" class="phone-mask" required>
                    </div>
                    <div class="form-group">
                        <label>Carga Horária Semanal *</label>
                        <select id="editFuncCargaHoraria" required>
                            <option value="20h">20 Horas Semanais</option>
                            <option value="25h">25 Horas Semanais</option>
                            <option value="30h">30 Horas Semanais</option>
                            <option value="40h">40 Horas Semanais</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Vínculo Empregatício *</label>
                        <select id="editFuncVinculo" required>
                            <option value="Efetivo">Efetivo / Concursado</option>
                            <option value="Contratado">Contratado / Temporário</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Bairro *</label>
                        <input type="text" id="editFuncBairro" required>
                    </div>
                    <div class="form-group full-width">
                        <label>Rua e Número *</label>
                        <input type="text" id="editFuncRuaNum" required>
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="action-btn" onclick="fecharModalEdicaoFunc()">Cancelar</button>
                    <button type="submit" class="btn-submit" style="padding: 6px 15px; margin-top:0;">Salvar Alterações</button>
                </div>
            </form>
        </div>
    </div>

    <footer>
        <p>&copy; EMEB Manoel de Medeiros Costa - São Bento, Maragogi/AL. Sistema de Controle Escolar.</p>
    </footer>

    <script>
        let alunos = JSON.parse(localStorage.getItem('emeb_alunos')) || [];
        let funcionarios = JSON.parse(localStorage.getItem('emeb_funcionarios')) || [];

        let currentEditType = null; 
        let currentEditId = null;

        document.addEventListener('DOMContentLoaded', () => {
            const inputAnoLetivo = document.getElementById('alunoAnoLetivo');
            if (inputAnoLetivo && !inputAnoLetivo.value) {
                inputAnoLetivo.value = new Date().getFullYear();
            }

            renderizarAlunos();
            renderizarFuncionarios();
            atualizarDashboard();
            aplicarMascaras();
            inicializarEstados();
            carregarSelectsRelatorios();

            window.addEventListener('click', (e) => {
                if (!e.target.closest('.dropdown')) {
                    fecharTodosDropdowns();
                }
            });
        });

        function toggleDropdown(dropdownId, event) {
            event.stopPropagation();
            const dropdown = document.getElementById(dropdownId);
            const isActive = dropdown.classList.contains('active');
            fecharTodosDropdowns();
            if (!isActive) {
                dropdown.classList.add('active');
            }
        }

        function fecharTodosDropdowns() {
            document.querySelectorAll('.dropdown').forEach(d => d.classList.remove('active'));
        }

        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(tab => tab.classList.remove('active'));
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('active'));

            document.getElementById(tabId).classList.add('active');
            
            const activeBtn = Array.from(document.querySelectorAll('.nav-btn')).find(btn => 
                btn.getAttribute('onclick') && btn.getAttribute('onclick').includes(tabId)
            );
            if (activeBtn) activeBtn.classList.add('active');

            if (tabId === 'dashboard') atualizarDashboard();
            if (tabId === 'relatorio-aluno' || tabId === 'relatorio-funcionario') carregarSelectsRelatorios();
        }

        function previewFoto(event, previewId) {
            const file = event.target.files[0];
            const previewContainer = document.getElementById(previewId);
            
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    previewContainer.innerHTML = `<img src="${e.target.result}" alt="Preview">`;
                    previewContainer.dataset.base64 = e.target.result;
                }
                reader.readAsDataURL(file);
            }
        }

        function verificarCargoProfessor() {
            const cargo = document.getElementById('funcCargo').value;
            const grupoArea = document.getElementById('grupoAreaAtuacao');
            const selectArea = document.getElementById('funcAreaAtuacao');

            if (cargo === 'Professor') {
                grupoArea.style.display = 'flex';
                selectArea.required = true;
            } else {
                grupoArea.style.display = 'none';
                selectArea.required = false;
                selectArea.value = '';
            }
        }

        function verificarCargoProfessorEdicao() {
            const cargo = document.getElementById('editFuncCargo').value;
            const grupoArea = document.getElementById('grupoEditAreaAtuacao');
            const selectArea = document.getElementById('editFuncAreaAtuacao');

            if (cargo === 'Professor') {
                grupoArea.style.display = 'flex';
                selectArea.required = true;
            } else {
                grupoArea.style.display = 'none';
                selectArea.required = false;
                selectArea.value = '';
            }
        }

        function inicializarEstados() {
            carregarEstados('alunoEstadoNasc');
            carregarEstados('arqEstadoNasc');
            carregarEstados('funcEstado');
        }

        function carregarEstados(elementId) {
            const selectUF = document.getElementById(elementId);
            if (!selectUF) return;

            fetch('https://servicodados.ibge.gov.br/api/v1/localidades/estados?orderBy=nome')
                .then(response => response.json())
                .then(estados => {
                    selectUF.innerHTML = '<option value="">Selecione o Estado</option>';
                    estados.forEach(uf => {
                        selectUF.innerHTML += `<option value="${uf.sigla}">${uf.nome} (${uf.sigla})</option>`;
                    });
                })
                .catch(() => {
                    selectUF.innerHTML = '<option value="">Erro ao carregar estados</option>';
                });
        }

        function carregarCidades(ufSigla, estadoElementId, cidadeElementId) {
            const selectCidade = document.getElementById(cidadeElementId);
            if (!selectCidade) return;

            if (!ufSigla) {
                selectCidade.innerHTML = '<option value="">Selecione o Estado primeiro</option>';
                selectCidade.disabled = true;
                return;
            }

            selectCidade.innerHTML = '<option value="">Carregando cidades...</option>';
            selectCidade.disabled = true;

            fetch(`https://servicodados.ibge.gov.br/api/v1/localidades/estados/${ufSigla}/municipios?orderBy=nome`)
                .then(response => response.json())
                .then(cidades => {
                    selectCidade.innerHTML = '<option value="">Selecione a Cidade</option>';
                    cidades.forEach(cidade => {
                        selectCidade.innerHTML += `<option value="${cidade.nome}">${cidade.nome}</option>`;
                    });
                    selectCidade.disabled = false;
                })
                .catch(() => {
                    selectCidade.innerHTML = '<option value="">Erro ao carregar cidades</option>';
                });
        }

        function aplicarMascaras() {
            document.querySelectorAll('.phone-mask').forEach(input => {
                input.addEventListener('input', (e) => {
                    let v = e.target.value.replace(/\D/g, '');
                    if (v.length > 11) v = v.substring(0, 11);
                    if (v.length > 10) {
                        v = v.replace(/^(\d{2})(\d{5})(\d{4})$/, '($1) $2-$3');
                    } else if (v.length > 5) {
                        v = v.replace(/^(\d{2})(\d{4})(\d{0,4})$/, '($1) $2-$3');
                    } else if (v.length > 2) {
                        v = v.replace(/^(\d{2})(\d{0,5})$/, '($1) $2');
                    } else {
                        v = v.replace(/^(\d*)$/, '($1');
                    }
                    e.target.value = v;
                });
            });

            document.querySelectorAll('.cpf-mask').forEach(input => {
                input.addEventListener('input', (e) => {
                    let v = e.target.value.replace(/\D/g, '');
                    if (v.length > 11) v = v.substring(0, 11);
                    v = v.replace(/(\d{3})(\d)/, '$1.$2');
                    v = v.replace(/(\d{3})(\d)/, '$1.$2');
                    v = v.replace(/(\d{3})(\d{1,2})$/, '$1-$2');
                    e.target.value = v;
                });
            });
        }

        function salvarAluno(event, isArquivo) {
            event.preventDefault();

            let prefix = isArquivo ? 'arq' : 'aluno';
            const dataNasc = document.getElementById(prefix + 'DataNasc').value;
            const dataFormatada = dataNasc ? new Date(dataNasc + 'T00:00:00').toLocaleDateString('pt-BR') : 'N/A';
            const previewContainer = document.getElementById(prefix + 'PhotoPreview');
            const fotoBase64 = previewContainer.dataset.base64 || '';

            let dataEntradaFormatada = 'N/A';
            let dataSaidaFormatada = 'N/A';
            let statusInicial = 'Matriculado';

            if (isArquivo) {
                const dEntrada = document.getElementById('arqDataEntrada').value;
                const dSaida = document.getElementById('arqDataSaida').value;
                dataEntradaFormatada = dEntrada ? new Date(dEntrada + 'T00:00:00').toLocaleDateString('pt-BR') : 'N/A';
                dataSaidaFormatada = dSaida ? new Date(dSaida + 'T00:00:00').toLocaleDateString('pt-BR') : 'N/A';
                statusInicial = document.getElementById('arqStatus').value;
            }

            const novoAluno = {
                id: Date.now(),
                foto: fotoBase64,
                nome: document.getElementById(prefix + 'Nome').value.trim(),
                dataNascimento: dataFormatada,
                dataNascRaw: dataNasc,
                cidadeNasc: document.getElementById(prefix + 'CidadeNasc').value,
                estadoNasc: document.getElementById(prefix + 'EstadoNasc').value,
                cpf: document.getElementById(prefix + 'Cpf').value.trim() || 'Não informado',
                anoLetivo: document.getElementById(prefix + 'AnoLetivo').value.trim() || '2026',
                ano: document.getElementById(prefix + 'Ano').value,
                turma: document.getElementById(prefix + 'Turma').value,
                dataEntrada: dataEntradaFormatada,
                dataSaida: dataSaidaFormatada,
                nomeMae: document.getElementById(prefix + 'NomeMae').value.trim(),
                telMae: document.getElementById(prefix + 'TelMae').value || 'Não informado',
                nomePai: document.getElementById(prefix + 'NomePai').value.trim() || 'Não informado',
                telPai: document.getElementById(prefix + 'TelPai').value || 'N/A',
                endereco: document.getElementById(prefix + 'Endereco').value.trim(),
                status: statusInicial,
                dataCadastro: new Date().toLocaleDateString('pt-BR')
            };

            alunos.push(novoAluno);
            localStorage.setItem('emeb_alunos', JSON.stringify(alunos));

            alert('Registro salvo com sucesso!');
            document.getElementById(isArquivo ? 'formArquivo' : 'formAluno').reset();
            if (!isArquivo) {
                document.getElementById('alunoAnoLetivo').value = new Date().getFullYear();
            }
            previewContainer.innerHTML = `<i class="fa-solid fa-user"></i>`;
            delete previewContainer.dataset.base64;
            
            const selectCidade = document.getElementById(prefix + 'CidadeNasc');
            selectCidade.innerHTML = '<option value="">Selecione o Estado primeiro</option>';
            selectCidade.disabled = true;

            renderizarAlunos();
            atualizarDashboard();
            switchTab('lista-alunos');
        }

        function renderizarAlunos() {
            const filterAnoLetivo = document.getElementById('filterAnoLetivo').value.toLowerCase();
            const filterAno = document.getElementById('filterAno').value;
            const filterTurma = document.getElementById('filterTurma').value;
            const search = document.getElementById('searchAluno').value.toLowerCase();

            const tbody = document.getElementById('tbody-alunos');
            tbody.innerHTML = '';

            const alunosFiltrados = alunos.filter(a => {
                const matchAnoLetivo = !filterAnoLetivo || (a.anoLetivo && a.anoLetivo.toLowerCase().includes(filterAnoLetivo));
                const matchAno = !filterAno || a.ano === filterAno;
                const matchTurma = !filterTurma || a.turma === filterTurma;
                const matchSearch = a.nome.toLowerCase().includes(search);
                return matchAnoLetivo && matchAno && matchTurma && matchSearch;
            });

            if (alunosFiltrados.length === 0) {
                tbody.innerHTML = `<tr><td colspan="10" style="text-align:center; color: #94a3b8; padding: 20px;">Nenhum aluno encontrado.</td></tr>`;
                return;
            }

            alunosFiltrados.forEach(a => {
                const tr = document.createElement('tr');

                let badgeClass = 'badge-matriculado';
                if (a.status === 'Transferido') badgeClass = 'badge-transferido';
                if (a.status === 'Desistência') badgeClass = 'badge-desistencia';
                if (a.status === 'Concluído') badgeClass = 'badge-concluido';

                const referenciaTurma = `${a.ano} - Turma ${a.turma} (${a.anoLetivo || 'N/A'})`;
                const periodoTexto = a.dataEntrada && a.dataEntrada !== 'N/A' ? `<small>Entrada: ${a.dataEntrada}</small><br><small>Saída: ${a.dataSaida}</small>` : '<small style="color:#94a3b8;">Não especificado</small>';
                const avatarHtml = a.foto ? `<img src="${a.foto}" class="table-avatar" alt="Foto">` : `<div class="table-avatar"><i class="fa-solid fa-user"></i></div>`;

                tr.innerHTML = `
                    <td>
                        <div style="display: flex; align-items: center;">
                            ${avatarHtml}
                            <div>
                                <strong>${a.nome}</strong><br>
                                <small style="color: #64748b;">CPF: ${a.cpf || 'N/A'}</small>
                            </div>
                        </div>
                    </td>
                    <td>${a.dataNascimento || 'N/A'}</td>
                    <td>${a.cidadeNasc ? `${a.cidadeNasc}/${a.estadoNasc}` : 'N/A'}</td>
                    <td>${referenciaTurma}</td>
                    <td>${periodoTexto}</td>
                    <td>
                        <small><strong>Mãe:</strong> ${a.nomeMae}</small><br>
                        <small><strong>Pai:</strong> ${a.nomePai}</small>
                    </td>
                    <td>
                        <small><i class="fa-solid fa-phone"></i> M: ${a.telMae}</small><br>
                        ${a.telPai !== 'N/A' ? `<small><i class="fa-solid fa-phone"></i> P: ${a.telPai}</small>` : ''}
                    </td>
                    <td>${a.endereco}</td>
                    <td><span class="badge ${badgeClass}" title="Clique para alterar o status" onclick="abrirModalStatus('aluno', ${a.id})">${a.status}</span></td>
                    <td class="action-col">
                        <button class="action-btn" title="Editar Cadastro Completo" onclick="abrirModalEdicaoAluno(${a.id})">
                            <i class="fa-solid fa-pen-to-square"></i>
                        </button>
                        <button class="action-btn" title="Excluir" onclick="excluirItem('aluno', ${a.id})">
                            <i class="fa-solid fa-trash" style="color: var(--accent-red);"></i>
                        </button>
                    </td>
                `;
                tbody.appendChild(tr);
            });
        }

        function abrirModalEdicaoAluno(id) {
            const a = alunos.find(item => item.id === id);
            if (!a) return;

            document.getElementById('editAlunoId').value = a.id;
            document.getElementById('editAlunoNome').value = a.nome;
            document.getElementById('editAlunoDataNasc').value = a.dataNascRaw || '';
            document.getElementById('editAlunoCpf').value = a.cpf !== 'Não informado' ? a.cpf : '';
            document.getElementById('editAlunoAnoLetivo').value = a.anoLetivo || '2026';
            document.getElementById('editAlunoAno').value = a.ano;
            document.getElementById('editAlunoTurma').value = a.turma;
            document.getElementById('editNomeMae').value = a.nomeMae;
            document.getElementById('editTelMae').value = a.telMae;
            document.getElementById('editNomePai').value = a.nomePai !== 'Não informado' ? a.nomePai : '';
            document.getElementById('editTelPai').value = a.telPai !== 'N/A' ? a.telPai : '';
            document.getElementById('editAlunoEndereco').value = a.endereco;

            const previewContainer = document.getElementById('editAlunoPhotoPreview');
            if (a.foto) {
                previewContainer.innerHTML = `<img src="${a.foto}" alt="Preview">`;
                previewContainer.dataset.base64 = a.foto;
            } else {
                previewContainer.innerHTML = `<i class="fa-solid fa-user"></i>`;
                delete previewContainer.dataset.base64;
            }
            document.getElementById('editAlunoFoto').value = '';

            document.getElementById('editAlunoModal').classList.add('active');
        }

        function fecharModalEdicaoAluno() {
            document.getElementById('editAlunoModal').classList.remove('active');
        }

        function salvarEdicaoAluno(event) {
            event.preventDefault();
            const id = parseInt(document.getElementById('editAlunoId').value);
            const a = alunos.find(item => item.id === id);

            if (a) {
                const dataNasc = document.getElementById('editAlunoDataNasc').value;
                const previewContainer = document.getElementById('editAlunoPhotoPreview');
                
                if (previewContainer.dataset.base64) {
                    a.foto = previewContainer.dataset.base64;
                }

                a.nome = document.getElementById('editAlunoNome').value.trim();
                a.dataNascRaw = dataNasc;
                a.dataNascimento = dataNasc ? new Date(dataNasc + 'T00:00:00').toLocaleDateString('pt-BR') : 'N/A';
                a.cpf = document.getElementById('editAlunoCpf').value.trim() || 'Não informado';
                a.anoLetivo = document.getElementById('editAlunoAnoLetivo').value.trim() || '2026';
                a.ano = document.getElementById('editAlunoAno').value;
                a.turma = document.getElementById('editAlunoTurma').value;
                a.nomeMae = document.getElementById('editNomeMae').value.trim();
                a.telMae = document.getElementById('editTelMae').value;
                a.nomePai = document.getElementById('editNomePai').value.trim() || 'Não informado';
                a.telPai = document.getElementById('editTelPai').value || 'N/A';
                a.endereco = document.getElementById('editAlunoEndereco').value.trim();

                localStorage.setItem('emeb_alunos', JSON.stringify(alunos));
                renderizarAlunos();
                atualizarDashboard();
                fecharModalEdicaoAluno();
                alert('Cadastro do aluno atualizado com sucesso!');
            }
        }

        function salvarFuncionario(event) {
            event.preventDefault();

            const dataAdmissao = document.getElementById('funcDataAdmissao').value;
            const dataFormatada = dataAdmissao ? new Date(dataAdmissao + 'T00:00:00').toLocaleDateString('pt-BR') : 'N/A';
            const cargo = document.getElementById('funcCargo').value;
            const areaAtuacao = document.getElementById('funcAreaAtuacao').value;
            const previewContainer = document.getElementById('funcPhotoPreview');
            const fotoBase64 = previewContainer.dataset.base64 || '';

            const novoFunc = {
                id: Date.now(),
                foto: fotoBase64,
                nome: document.getElementById('funcNome').value.trim(),
                cargo: cargo,
                areaAtuacao: cargo === 'Professor' ? areaAtuacao : null,
                telefone: document.getElementById('funcTelefone').value,
                cargaHoraria: document.getElementById('funcCargaHoraria').value,
                vinculo: document.getElementById('funcVinculo').value,
                dataAdmissao: dataFormatada,
                dataAdmissaoRaw: dataAdmissao,
                ruaNum: document.getElementById('funcRuaNum').value.trim(),
                bairro: document.getElementById('funcBairro').value.trim(),
                cidade: document.getElementById('funcCidade').value,
                estado: document.getElementById('funcEstado').value,
                status: 'Ativo'
            };

            funcionarios.push(novoFunc);
            localStorage.setItem('emeb_funcionarios', JSON.stringify(funcionarios));

            alert('Funcionário cadastrado com sucesso!');
            document.getElementById('formFuncionario').reset();
            previewContainer.innerHTML = `<i class="fa-solid fa-user-tie"></i>`;
            delete previewContainer.dataset.base64;
            verificarCargoProfessor();
            
            const selectCidade = document.getElementById('funcCidade');
            selectCidade.innerHTML = '<option value="">Selecione o Estado primeiro</option>';
            selectCidade.disabled = true;

            renderizarFuncionarios();
            switchTab('lista-funcionarios');
        }

        function renderizarFuncionarios() {
            const filterCargo = document.getElementById('filterCargo').value;
            const filterStatus = document.getElementById('filterStatusFunc').value;
            const search = document.getElementById('searchFunc').value.toLowerCase();

            const tbody = document.getElementById('tbody-funcionarios');
            tbody.innerHTML = '';

            const funcsFiltrados = funcionarios.filter(f => {
                const matchCargo = !filterCargo || f.cargo === filterCargo;
                const matchStatus = !filterStatus || f.status === filterStatus;
                const matchSearch = f.nome.toLowerCase().includes(search);
                return matchCargo && matchStatus && matchSearch;
            });

            if (funcsFiltrados.length === 0) {
                tbody.innerHTML = `<tr><td colspan="9" style="text-align:center; color: #94a3b8; padding: 20px;">Nenhum funcionário encontrado.</td></tr>`;
                return;
            }

            funcsFiltrados.forEach(f => {
                const tr = document.createElement('tr');

                let badgeClass = 'badge-ativo';
                if (f.status === 'Licença') badgeClass = 'badge-licenca';
                if (f.status === 'Desligado') badgeClass = 'badge-desligado';

                const cargoTexto = f.cargo === 'Professor' && f.areaAtuacao 
                    ? `Professor(a) - ${f.areaAtuacao}` 
                    : f.cargo;

                const enderecoCompleto = f.ruaNum ? `${f.ruaNum}, Bairro: ${f.bairro} - ${f.cidade}/${f.estado}` : (f.endereco || 'Não informado');
                const avatarHtml = f.foto ? `<img src="${f.foto}" class="table-avatar" alt="Foto">` : `<div class="table-avatar"><i class="fa-solid fa-user-tie"></i></div>`;

                tr.innerHTML = `
                    <td>
                        <div style="display: flex; align-items: center;">
                            ${avatarHtml}
                            <strong>${f.nome}</strong>
                        </div>
                    </td>
                    <td>${cargoTexto}</td>
                    <td>${f.cargaHoraria || 'N/A'}</td>
                    <td>${f.vinculo || 'N/A'}</td>
                    <td>${f.dataAdmissao || 'N/A'}</td>
                    <td>${f.telefone}</td>
                    <td>${enderecoCompleto}</td>
                    <td><span class="badge ${badgeClass}" title="Clique para alterar o status" onclick="abrirModalStatus('funcionario', ${f.id})">${f.status}</span></td>
                    <td class="action-col">
                        <button class="action-btn" title="Editar Cadastro Completo" onclick="abrirModalEdicaoFunc(${f.id})">
                            <i class="fa-solid fa-pen-to-square"></i>
                        </button>
                        <button class="action-btn" title="Excluir" onclick="excluirItem('funcionario', ${f.id})">
                            <i class="fa-solid fa-trash" style="color: var(--accent-red);"></i>
                        </button>
                    </td>
                `;
                tbody.appendChild(tr);
            });
        }

        function abrirModalEdicaoFunc(id) {
            const f = funcionarios.find(item => item.id === id);
            if (!f) return;

            document.getElementById('editFuncId').value = f.id;
            document.getElementById('editFuncNome').value = f.nome;
            document.getElementById('editFuncCargo').value = f.cargo;
            document.getElementById('editFuncTelefone').value = f.telefone;
            document.getElementById('editFuncCargaHoraria').value = f.cargaHoraria;
            document.getElementById('editFuncVinculo').value = f.vinculo;
            document.getElementById('editFuncBairro').value = f.bairro || '';
            document.getElementById('editFuncRuaNum').value = f.ruaNum || '';

            const previewContainer = document.getElementById('editFuncPhotoPreview');
            if (f.foto) {
                previewContainer.innerHTML = `<img src="${f.foto}" alt="Preview">`;
                previewContainer.dataset.base64 = f.foto;
            } else {
                previewContainer.innerHTML = `<i class="fa-solid fa-user-tie"></i>`;
                delete previewContainer.dataset.base64;
            }
            document.getElementById('editFuncFoto').value = '';

            verificarCargoProfessorEdicao();
            if (f.cargo === 'Professor' && f.areaAtuacao) {
                document.getElementById('editFuncAreaAtuacao').value = f.areaAtuacao;
            }

            document.getElementById('editFuncModal').classList.add('active');
        }

        function fecharModalEdicaoFunc() {
            document.getElementById('editFuncModal').classList.remove('active');
        }

        function salvarEdicaoFuncionario(event) {
            event.preventDefault();
            const id = parseInt(document.getElementById('editFuncId').value);
            const f = funcionarios.find(item => item.id === id);

            if (f) {
                const cargo = document.getElementById('editFuncCargo').value;
                const previewContainer = document.getElementById('editFuncPhotoPreview');

                if (previewContainer.dataset.base64) {
                    f.foto = previewContainer.dataset.base64;
                }

                f.nome = document.getElementById('editFuncNome').value.trim();
                f.cargo = cargo;
                f.areaAtuacao = cargo === 'Professor' ? document.getElementById('editFuncAreaAtuacao').value : null;
                f.telefone = document.getElementById('editFuncTelefone').value;
                f.cargaHoraria = document.getElementById('editFuncCargaHoraria').value;
                f.vinculo = document.getElementById('editFuncVinculo').value;
                f.bairro = document.getElementById('editFuncBairro').value.trim();
                f.ruaNum = document.getElementById('editFuncRuaNum').value.trim();

                localStorage.setItem('emeb_funcionarios', JSON.stringify(funcionarios));
                renderizarFuncionarios();
                atualizarDashboard();
                fecharModalEdicaoFunc();
                alert('Cadastro do funcionário atualizado com sucesso!');
            }
        }

        function abrirModalStatus(tipo, id) {
            currentEditType = tipo;
            currentEditId = id;

            const select = document.getElementById('modalStatusSelect');
            select.innerHTML = '';

            if (tipo === 'aluno') {
                const item = alunos.find(a => a.id === id);
                document.getElementById('modalItemNome').innerText = `Aluno: ${item.nome}`;
                ['Matriculado', 'Transferido', 'Desistência', 'Concluído'].forEach(s => {
                    select.innerHTML += `<option value="${s}" ${item.status === s ? 'selected' : ''}>${s}</option>`;
                });
            } else {
                const item = funcionarios.find(f => f.id === id);
                document.getElementById('modalItemNome').innerText = `Funcionário: ${item.nome}`;
                ['Ativo', 'Licença', 'Desligado'].forEach(s => {
                    select.innerHTML += `<option value="${s}" ${item.status === s ? 'selected' : ''}>${s}</option>`;
                });
            }

            document.getElementById('statusModal').classList.add('active');
        }

        function fecharModalStatus() {
            document.getElementById('statusModal').classList.remove('active');
        }

        function confirmarAlteracaoStatus() {
            const novoStatus = document.getElementById('modalStatusSelect').value;

            if (currentEditType === 'aluno') {
                const aluno = alunos.find(a => a.id === currentEditId);
                if (aluno) aluno.status = novoStatus;
                localStorage.setItem('emeb_alunos', JSON.stringify(alunos));
                renderizarAlunos();
            } else {
                const func = funcionarios.find(f => f.id === currentEditId);
                if (func) func.status = novoStatus;
                localStorage.setItem('emeb_funcionarios', JSON.stringify(funcionarios));
                renderizarFuncionarios();
            }

            fecharModalStatus();
            atualizarDashboard();
        }

        function excluirItem(tipo, id) {
            if (!confirm('Tem certeza que deseja excluir este registro?')) return;

            if (tipo === 'aluno') {
                alunos = alunos.filter(a => a.id !== id);
                localStorage.setItem('emeb_alunos', JSON.stringify(alunos));
                renderizarAlunos();
            } else {
                funcionarios = funcionarios.filter(f => f.id !== id);
                localStorage.setItem('emeb_funcionarios', JSON.stringify(funcionarios));
                renderizarFuncionarios();
            }
            atualizarDashboard();
            carregarSelectsRelatorios();
        }

        function carregarSelectsRelatorios() {
            const selectAluno = document.getElementById('selectRelatorioAluno');
            const selectFunc = document.getElementById('selectRelatorioFunc');

            if (selectAluno) {
                selectAluno.innerHTML = '<option value="">Selecione um aluno...</option>';
                alunos.forEach(a => {
                    selectAluno.innerHTML += `<option value="${a.id}">${a.nome} (${a.ano} - Turma ${a.turma} / ${a.anoLetivo || 'N/A'})</option>`;
                });
            }

            if (selectFunc) {
                selectFunc.innerHTML = '<option value="">Selecione um funcionário...</option>';
                funcionarios.forEach(f => {
                    selectFunc.innerHTML += `<option value="${f.id}">${f.nome} (${f.cargo})</option>`;
                });
            }
        }

        function gerarRelatorioAlunoEspecifico(id) {
            const container = document.getElementById('containerRelatorioAluno');
            if (!id) {
                container.innerHTML = `<p style="text-align: center; color: #94a3b8;">Nenhum aluno selecionado.</p>`;
                return;
            }

            const a = alunos.find(item => item.id == id);
            if (!a) return;

            const fotoTag = a.foto ? `<img src="${a.foto}" style="width: 80px; height: 80px; border-radius: 50%; object-fit: cover; border: 2px solid var(--primary-blue);">` : `<div style="width: 80px; height: 80px; border-radius: 50%; background: #e2e8f0; display:flex; align-items:center; justify-content:center; color:#64748b;"><i class="fa-solid fa-user fa-2x"></i></div>`;
            const periodoInfo = a.dataEntrada && a.dataEntrada !== 'N/A' ? `<p><strong>Período na Escola:</strong> ${a.dataEntrada} até ${a.dataSaida}</p>` : '';

            container.innerHTML = `
                <div style="display: flex; align-items: center; gap: 20px; border-bottom: 2px solid #e2e8f0; padding-bottom: 15px; margin-bottom: 15px;">
                    ${fotoTag}
                    <div>
                        <h3 style="color: var(--primary-blue); font-size: 1.3rem;">${a.nome}</h3>
                        <p><strong>Status:</strong> ${a.status} | <strong>Ano Letivo/Série/Turma:</strong> ${a.ano} - Turma ${a.turma} (${a.anoLetivo || 'N/A'})</p>
                    </div>
                </div>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 12px; font-size: 0.95rem;">
                    <p><strong>CPF:</strong> ${a.cpf}</p>
                    <p><strong>Data de Nascimento:</strong> ${a.dataNascimento}</p>
                    <p><strong>Naturalidade:</strong> ${a.cidadeNasc ? `${a.cidadeNasc}/${a.estadoNasc}` : 'N/A'}</p>
                    ${periodoInfo}
                    <p><strong>Nome da Mãe:</strong> ${a.nomeMae} (${a.telMae})</p>
                    <p><strong>Nome do Pai:</strong> ${a.nomePai} (${a.telPai})</p>
                    <p style="grid-column: 1 / -1;"><strong>Endereço:</strong> ${a.endereco}</p>
                </div>
            `;
        }

        function gerarRelatorioFuncEspecifico(id) {
            const container = document.getElementById('containerRelatorioFunc');
            if (!id) {
                container.innerHTML = `<p style="text-align: center; color: #94a3b8;">Nenhum funcionário selecionado.</p>`;
                return;
            }

            const f = funcionarios.find(item => item.id == id);
            if (!f) return;

            const fotoTag = f.foto ? `<img src="${f.foto}" style="width: 80px; height: 80px; border-radius: 50%; object-fit: cover; border: 2px solid var(--primary-blue);">` : `<div style="width: 80px; height: 80px; border-radius: 50%; background: #e2e8f0; display:flex; align-items:center; justify-content:center; color:#64748b;"><i class="fa-solid fa-user-tie fa-2x"></i></div>`;
            const cargoTexto = f.cargo === 'Professor' && f.areaAtuacao ? `Professor(a) - ${f.areaAtuacao}` : f.cargo;

            container.innerHTML = `
                <div style="display: flex; align-items: center; gap: 20px; border-bottom: 2px solid #e2e8f0; padding-bottom: 15px; margin-bottom: 15px;">
                    ${fotoTag}
                    <div>
                        <h3 style="color: var(--primary-blue); font-size: 1.3rem;">${f.nome}</h3>
                        <p><strong>Cargo:</strong> ${cargoTexto} | <strong>Status:</strong> ${f.status}</p>
                    </div>
                </div>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 12px; font-size: 0.95rem;">
                    <p><strong>Telefone:</strong> ${f.telefone}</p>
                    <p><strong>Carga Horária:</strong> ${f.cargaHoraria}</p>
                    <p><strong>Vínculo:</strong> ${f.vinculo}</p>
                    <p><strong>Admissão:</strong> ${f.dataAdmissao}</p>
                    <p style="grid-column: 1 / -1;"><strong>Endereço:</strong> ${f.ruaNum}, Bairro: ${f.bairro} - ${f.cidade}/${f.estado}</p>
                </div>
            `;
        }

        function atualizarDashboard() {
            const alunosAtivos = alunos.filter(a => a.status === 'Matriculado').length;
            const funcsAtivos = funcionarios.filter(f => f.status === 'Ativo').length;
            const alunosSaida = alunos.filter(a => a.status === 'Transferido' || a.status === 'Desistência' || a.status === 'Concluído').length;
            const totalGeral = alunos.length + funcionarios.length;

            document.getElementById('stat-alunos-ativos').innerText = alunosAtivos;
            document.getElementById('stat-func-ativos').innerText = funcsAtivos;
            document.getElementById('stat-alunos-saida').innerText = alunosSaida;
            document.getElementById('stat-total-geral').innerText = totalGeral;

            const series = ['1º Ano', '2º Ano', '3º Ano', '4º Ano', '5º Ano', '6º Ano', '7º Ano', '8º Ano', '9º Ano'];
            const tbodyResumo = document.getElementById('tbody-resumo-series');
            tbodyResumo.innerHTML = '';

            series.forEach(serie => {
                const dosAlunos = alunos.filter(a => a.ano === serie && a.status === 'Matriculado');
                const trans = alunos.filter(a => a.ano === serie && a.status === 'Transferido').length;
                const des = alunos.filter(a => a.ano === serie && a.status === 'Desistência').length;
                const totalSerie = alunos.filter(a => a.ano === serie).length;

                const tr = document.createElement('tr');
                tr.innerHTML = `
                    <td><strong>${serie}</strong></td>
                    <td><span class="badge badge-matriculado">${dosAlunos.length}</span></td>
                    <td><span class="badge badge-transferido">${trans}</span></td>
                    <td><span class="badge badge-desistencia">${des}</span></td>
                    <td><strong>${totalSerie}</strong></td>
                `;
                tbodyResumo.appendChild(tr);
            });
        }

        function atualizarListaPreviaMigracao() {
            const origemAnoLetivo = document.getElementById('origemAnoLetivo').value.trim();
            const origemAno = document.getElementById('origemAno').value;
            const origemTurma = document.getElementById('origemTurma').value;
            const tbody = document.getElementById('tbody-previa-migracao');
            const contador = document.getElementById('contadorAlunosMigracao');
            
            tbody.innerHTML = '';

            if (!origemAnoLetivo || !origemAno || !origemTurma) {
                contador.innerText = '0';
                tbody.innerHTML = `<tr><td colspan="3" style="text-align:center; color: #94a3b8;">Preencha o ano, série e turma de origem acima.</td></tr>`;
                return;
            }

            const alunosFiltrados = alunos.filter(a => a.anoLetivo === origemAnoLetivo && a.ano === origemAno && a.turma === origemTurma && a.status === 'Matriculado');
            contador.innerText = alunosFiltrados.length;

            if (alunosFiltrados.length === 0) {
                tbody.innerHTML = `<tr><td colspan="3" style="text-align:center; color: #94a3b8;">Nenhum aluno ativo encontrado para esta referência.</td></tr>`;
                return;
            }

            alunosFiltrados.forEach(a => {
                const tr = document.createElement('tr');
                tr.innerHTML = `
                    <td><strong>${a.nome}</strong></td>
                    <td><span class="badge badge-matriculado">${a.status}</span></td>
                    <td>${a.ano} - Turma ${a.turma} (${a.anoLetivo})</td>
                `;
                tbody.appendChild(tr);
            });
        }

        function executarMigracaoLote() {
            const origemAnoLetivo = document.getElementById('origemAnoLetivo').value.trim();
            const origemAno = document.getElementById('origemAno').value;
            const origemTurma = document.getElementById('origemTurma').value;
            const destinoAnoLetivo = document.getElementById('destinoAnoLetivo').value.trim();
            const destinoAno = document.getElementById('destinoAno').value;
            const destinoTurma = document.getElementById('destinoTurma').value;

            if (!origemAnoLetivo || !origemAno || !origemTurma || !destinoAnoLetivo || !destinoAno) {
                alert('Por favor, preencha todos os campos obrigatórios de origem e destino.');
                return;
            }

            const alunosParaMigrar = alunos.filter(a => a.anoLetivo === origemAnoLetivo && a.ano === origemAno && a.turma === origemTurma && a.status === 'Matriculado');

            if (alunosParaMigrar.length === 0) {
                alert('Não há alunos ativos para migrar com os filtros informados.');
                return;
            }

            if (!confirm(`Atenção: Você vai migrar ${alunosParaMigrar.length} aluno(s) do ${origemAno} Turma ${origemTurma} (${origemAnoLetivo}) para ${destinoAno} ${destinoAno !== 'Concluído' ? 'Turma ' + destinoTurma : ''} (${destinoAnoLetivo}). Deseja confirmar?`)) {
                return;
            }

            let alterados = 0;
            alunos.forEach(a => {
                if (a.anoLetivo === origemAnoLetivo && a.ano === origemAno && a.turma === origemTurma && a.status === 'Matriculado') {
                    if (destinoAno === 'Concluído') {
                        a.status = 'Concluído';
                        a.anoLetivo = destinoAnoLetivo;
                    } else {
                        a.ano = destinoAno;
                        a.turma = destinoTurma;
                        a.anoLetivo = destinoAnoLetivo;
                    }
                    alterados++;
                }
            });

            localStorage.setItem('emeb_alunos', JSON.stringify(alunos));

            renderizarAlunos();
            atualizarDashboard();
            carregarSelectsRelatorios();
            atualizarListaPreviaMigracao();

            alert(`Migração realizada com sucesso! Total de alunos atualizados para o ano ${destinoAnoLetivo}: ${alterados}`);
        }

        function exportarParaExcel(tableId, filename, sheetName) {
            const tabela = document.getElementById(tableId);
            if (!tabela) return;

            const clone = tabela.cloneNode(true);
            clone.querySelectorAll('.action-col').forEach(el => el.remove());
            clone.querySelectorAll('.table-avatar, img').forEach(el => el.remove());

            const wb = XLSX.utils.table_to_book(clone, { sheet: sheetName });
            XLSX.writeFile(wb, filename);
        }

        function imprimirTabela(tableId, titulo) {
            const tabelaOriginal = document.getElementById(tableId);
            if (!tabelaOriginal) return;

            const tabelaClonada = tabelaOriginal.cloneNode(true);
            tabelaClonada.querySelectorAll('.action-col').forEach(col => col.remove());

            const dataEmissao = new Date().toLocaleDateString('pt-BR');
            const horaEmissao = new Date().toLocaleTimeString('pt-BR');

            const janelaImpressao = window.open('', '_blank', 'width=900,height=600');

            janelaImpressao.document.write(`
                <!DOCTYPE html>
                <html lang="pt-BR">
                <head>
                    <meta charset="UTF-8">
                    <title>${titulo} - EMEB Manoel de Medeiros Costa</title>
                    <style>
                        body { font-family: Arial, sans-serif; padding: 20px; color: #000; }
                        .header { text-align: center; border-bottom: 2px solid #000; padding-bottom: 10px; margin-bottom: 20px; }
                        .header h1 { font-size: 1.3rem; margin: 0; text-transform: uppercase; }
                        .header p { margin: 3px 0; font-size: 0.85rem; }
                        .title { font-size: 1.1rem; font-weight: bold; text-transform: uppercase; margin: 15px 0 10px; }
                        table { width: 100%; border-collapse: collapse; margin-top: 10px; font-size: 0.85rem; }
                        th, td { border: 1px solid #000; padding: 8px; text-align: left; }
                        th { background-color: #f2f2f2; font-weight: bold; }
                        .table-avatar { width: 35px; height: 35px; border-radius: 50%; object-fit: cover; display: inline-block; vertical-align: middle; margin-right: 6px; }
                        footer { margin-top: 20px; font-size: 0.8rem; text-align: right; font-style: italic; }
                    </style>
                </head>
                <body>
                    <div class="header">
                        <h1>EMEB Manoel de Medeiros Costa</h1>
                        <p>Direção: Valdineide Alves da Silva</p>
                        <p>Povoado São Bento, Maragogi / AL - Ensino Fundamental</p>
                    </div>
                    <div class="title">${titulo}</div>
                    <div>${tabelaClonada.outerHTML}</div>
                    <footer>Emitido em ${dataEmissao} às ${horaEmissao}</footer>
                </body>
                </html>
            `);

            janelaImpressao.document.close();
            janelaImpressao.focus();

            setTimeout(() => {
                janelaImpressao.print();
                janelaImpressao.close();
            }, 250);
        }
    </script>
</body>
</html>
