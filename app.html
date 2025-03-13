<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <title>Economiza Kids</title>
    <style>
        :root {
            --dark-bg: #1a1a1a;
            --accent: #00ff90;
            --text-light: #e0e0e0;
            --neon: #00ff90;
            --shadow: 0 0 40px rgba(0,255,144,0.8);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            transition: all 0.3s ease;
        }

        body {
            background: var(--dark-bg);
            color: var(--text-light);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            overflow-x: hidden;
        }

        header {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 1.5rem;
            background: rgba(26,26,26,0.9);
            backdrop-filter: blur(10px);
            z-index: 1000;
            box-shadow: var(--shadow);
        }

        header h1 {
            font-size: 2.8rem;
            text-align: center;
            text-shadow: 0 0 20px var(--neon);
            margin-bottom: 1rem;
        }

        nav {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 0 1rem;
            gap: 0.5rem;
        }

        nav a {
            color: var(--text-light);
            text-decoration: none;
            font-size: 1.1rem;
            padding: 0.8rem 1.5rem;
            border-radius: 20px;
            transition: 0.3s;
        }

        nav a:hover {
            background: rgba(0,255,144,0.2);
            text-shadow: 0 0 15px var(--neon);
        }

        main {
            flex: 1;
            padding: 8rem 2rem 2rem;
            min-height: calc(100vh - 6rem);
        }

        .section {
            background: rgba(33,33,33,0.7);
            border-radius: 20px;
            padding: 2.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 8px 30px rgba(0,255,144,0.3);
        }

        .progress-container {
            display: flex;
            align-items: center;
            gap: 2rem;
            margin-top: 2rem;
        }

        .progress-bar {
            flex: 1;
            height: 25px;
            background: #2d2d2d;
            border-radius: 15px;
            position: relative;
            overflow: hidden;
        }

        .progress {
            height: 100%;
            width: 70%;
            background: linear-gradient(90deg, var(--accent), #00ff00);
            border-radius: 15px;
            transition: width 0.7s ease;
        }

        .values {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
            font-size: 1.1rem;
        }

        .history-list {
            list-style: none;
            padding: 0;
            margin-top: 1.5rem;
        }

        .history-item {
            background: rgba(33,33,33,0.5);
            padding: 1.2rem;
            margin-bottom: 1rem;
            border-radius: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            animation: fadeIn 1s;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
        }

        .achievements {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .achievement {
            background: rgba(33,33,33,0.5);
            padding: 2rem;
            border-radius: 20px;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }

        .achievement::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, var(--accent), transparent);
            animation: achievementShine 2s infinite;
        }

        @keyframes achievementShine {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .achievement:hover {
            transform: scale(1.03);
            box-shadow: var(--shadow);
        }

        .note-form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin-top: 1.5rem;
            margin-bottom: 1.5rem;
        }

        input, .input-amount {
            flex: 1;
            padding: 1rem;
            background: rgba(255,255,255,0.1);
            border: none;
            border-radius: 15px;
            color: var(--text-light);
            font-size: 1rem;
        }

        button {
            padding: 1rem 2rem;
            background: var(--accent);
            color: var(--dark-bg);
            font-weight: bold;
            border: none;
            border-radius: 15px;
            box-shadow: 0 0 10px var(--accent);
            cursor: pointer;
        }

        button:hover {
            background: #00ff00;
            transform: translateY(-2px);
        }

        .action-buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            z-index: 2000;
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background: var(--dark-bg);
            padding: 2rem;
            border-radius: 20px;
            width: 90%;
            max-width: 500px;
            box-shadow: var(--shadow);
        }

        .close {
            float: right;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--accent);
        }

        .add-amount {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1.5rem;
        }

        @media (max-width: 768px) {
            header {
                padding: 1rem;
            }

            header h1 {
                font-size: 2rem;
            }

            nav {
                justify-content: center;
            }

            nav a {
                font-size: 0.9rem;
                padding: 0.6rem 1rem;
                text-align: center;
                flex-grow: 1;
            }

            main {
                padding: 7rem 1rem 1rem;
            }

            .section {
                padding: 1.5rem;
            }

            .progress-container {
                flex-direction: column;
                align-items: stretch;
            }

            .note-form {
                flex-direction: column;
            }

            .action-buttons {
                flex-direction: column;
            }

            .add-amount {
                flex-direction: column;
            }
        }

        @media (max-width: 480px) {
            header h1 {
                font-size: 1.8rem;
            }

            .section {
                padding: 1rem;
            }

            .achievement {
                padding: 1.5rem;
            }

            .history-item {
                flex-direction: column;
                align-items: flex-start;
                gap: 0.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Economiza Kids</h1>
        <nav>
            <a href="#savings">Economizado</a>
            <a href="#history">Histórico</a>
            <a href="#achievements">Conquistas</a>
            <a href="#advanced">Avançado</a>
        </nav>
    </header>

    <main>
        <section class="section" id="savings">
            <h2>Economias Atuais</h2>
            <div class="progress-container">
                <div class="progress-bar">
                    <div class="progress" id="savings-progress"></div>
                </div>
                <div class="values">
                    <p>Total: <span id="total-amount">R$ 250,00</span></p>
                    <p>Objetivo: <span id="goal-amount">R$ 500,00</span></p>
                    <p>Falta: <span id="remaining-amount">R$ 250,00</span></p>
                </div>
            </div>
            <div class="add-amount">
                <input type="text" id="user-name" placeholder="Seu nome..." class="input-amount">
                <input type="number" id="deposit-amount" placeholder="Valor a adicionar..." step="0.01" min="0" class="input-amount">
                <button id="add-deposit">Adicionar Depósito</button>
            </div>
        </section>

        <section class="section" id="history">
            <h2>Histórico de Depósitos</h2>
            <ul class="history-list" id="deposits-history">
                <li class="history-item">10/03/2024 - +R$ 50,00</li>
                <li class="history-item">05/03/2024 - +R$ 100,00</li>
                <li class="history-item">01/03/2024 - +R$ 100,00</li>
            </ul>
        </section>

        <section class="section" id="achievements">
            <h2>Seus Desafios Conquistados</h2>
            <div class="achievements" id="achievements-container">
                <div class="achievement">
                    <h3>Primeiro Passo</h3>
                    <p>Depositou R$ 50</p>
                </div>
                <div class="achievement">
                    <h3>Metade do Caminho</h3>
                    <p>Depositou R$ 250</p>
                </div>
            </div>
        </section>

        <section class="section" id="advanced">
            <h2>Ferramentas Especiais</h2>
            <div class="note-form">
                <input type="text" id="note-input" placeholder="Escreva uma nota..." required>
                <button id="save-note">Salvar Nota</button>
            </div>
            <div class="action-buttons">
                <button id="edit-goal">Editar Objetivo</button>
                <button id="clear-history">Limpar Histórico</button>
            </div>
        </section>
    </main>

    <div class="modal" id="goal-modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>Definir Novo Objetivo</h2>
            <div class="note-form">
                <input type="number" id="new-goal" placeholder="Novo objetivo (R$)" step="0.01" min="0" required>
                <button id="save-goal">Salvar Objetivo</button>
            </div>
        </div>
    </div>

    <!-- Modal para objetivo concluído -->
    <div class="modal" id="goal-completed-modal">
        <div class="modal-content">
            <h2>🎉 Parabéns! Objetivo Alcançado! 🎉</h2>
            <p>Você atingiu seu objetivo de economia. Deseja criar um novo objetivo?</p>
            <div class="note-form">
                <input type="text" id="goal-name" placeholder="Nome do objetivo (ex: Bicicleta)" required>
                <input type="number" id="completed-new-goal" placeholder="Valor do novo objetivo (R$)" step="0.01" min="0" required>
                <div class="action-buttons">
                    <button id="archive-goal">Arquivar e Criar Novo</button>
                    <button id="close-completed-modal" class="secondary-button">Fechar</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Variáveis globais
        let totalAmount = 250.00;
        let goalAmount = 500.00;
        let currentGoalName = "Objetivo Inicial";
        let archivedGoals = [];
        let deposits = [
            { date: '10/03/2024', amount: 50.00, user: 'SISTEMA' },
            { date: '05/03/2024', amount: 100.00, user: 'SISTEMA' },
            { date: '01/03/2024', amount: 100.00, user: 'SISTEMA' }
        ];
        
        // Funções para salvar e carregar dados do localStorage
        function saveDataToLocalStorage() {
            localStorage.setItem('economizaKids_total', totalAmount.toString());
            localStorage.setItem('economizaKids_goal', goalAmount.toString());
            localStorage.setItem('economizaKids_goalName', currentGoalName);
            localStorage.setItem('economizaKids_deposits', JSON.stringify(deposits));
            localStorage.setItem('economizaKids_archivedGoals', JSON.stringify(archivedGoals));
        }
        
        function loadDataFromLocalStorage() {
            const savedTotal = localStorage.getItem('economizaKids_total');
            const savedGoal = localStorage.getItem('economizaKids_goal');
            const savedGoalName = localStorage.getItem('economizaKids_goalName');
            const savedDeposits = localStorage.getItem('economizaKids_deposits');
            const savedArchivedGoals = localStorage.getItem('economizaKids_archivedGoals');
            
            if (savedTotal) {
                totalAmount = parseFloat(savedTotal);
            }
            
            if (savedGoal) {
                goalAmount = parseFloat(savedGoal);
            }
            
            if (savedGoalName) {
                currentGoalName = savedGoalName;
            }
            
            if (savedDeposits) {
                deposits = JSON.parse(savedDeposits);
            }
            
            if (savedArchivedGoals) {
                archivedGoals = JSON.parse(savedArchivedGoals);
            }
        }
        
        // Função para formatar valores monetários
        function formatCurrency(value) {
            return 'R$ ' + value.toFixed(2).replace('.', ',');
        }
        
        // Função para atualizar o progresso
        function updateProgress() {
            const progress = document.getElementById('savings-progress');
            const totalSpan = document.getElementById('total-amount');
            const goalSpan = document.getElementById('goal-amount');
            const remainingSpan = document.getElementById('remaining-amount');
            
            const progressPercentage = Math.min((totalAmount / goalAmount) * 100, 100);
            const remaining = Math.max(goalAmount - totalAmount, 0);
            
            progress.style.width = `${progressPercentage}%`;
            totalSpan.textContent = formatCurrency(totalAmount);
            goalSpan.textContent = formatCurrency(goalAmount);
            remainingSpan.textContent = formatCurrency(remaining);
            
            // Verificar e atualizar conquistas
            checkAchievements();
            
            // Verificar se o objetivo foi alcançado
            checkGoalCompletion();
            
            // Salvar dados atualizados
            saveDataToLocalStorage();
        }
        
        // Função para atualizar o histórico
        function updateHistory() {
            const historyList = document.getElementById('deposits-history');
            historyList.innerHTML = '';
            
            deposits.forEach(deposit => {
                const item = document.createElement('li');
                item.className = 'history-item';
                const userName = deposit.user ? `${deposit.user} - ` : '';
                item.textContent = `${deposit.date} - ${userName}+${formatCurrency(deposit.amount)}`;
                historyList.prepend(item); // Adiciona no início da lista
            });
            
            // Salvar dados atualizados
            saveDataToLocalStorage();
        }
        
        // Função para verificar conquistas
        function checkAchievements() {
            const achievementsContainer = document.getElementById('achievements-container');
            
            // Limpar conquistas existentes
            achievementsContainer.innerHTML = '';
            
            // Definição das conquistas possíveis
            const possibleAchievements = [
                { name: 'Primeiro Passo', description: 'Depositou R$ 50', threshold: 50 },
                { name: 'Progredindo', description: 'Depositou R$ 100', threshold: 100 },
                { name: 'Metade do Caminho', description: 'Depositou R$ 250', threshold: 250 },
                { name: 'Quase Lá', description: 'Depositou R$ 400', threshold: 400 },
                { name: 'Objetivo Alcançado', description: 'Objetivo 100% Completo', threshold: goalAmount }
            ];
            
            // Verificar cada conquista
            possibleAchievements.forEach(achievement => {
                if (totalAmount >= achievement.threshold) {
                    const div = document.createElement('div');
                    div.className = 'achievement';
                    div.innerHTML = `
                        <h3>${achievement.name}</h3>
                        <p>${achievement.description}</p>
                    `;
                    achievementsContainer.appendChild(div);
                }
            });
        }
        
        // Função para adicionar depósito
        function addDeposit() {
            const amountInput = document.getElementById('deposit-amount');
            const userNameInput = document.getElementById('user-name');
            const amount = parseFloat(amountInput.value);
            let userName = userNameInput.value.trim();
            
            if (isNaN(amount) || amount <= 0) {
                alert('Por favor, insira um valor válido maior que zero.');
                return;
            }
            
            // Converter o nome do usuário para maiúsculas
            userName = userName ? userName.toUpperCase() : 'SISTEMA';
            
            // Obter a data atual
            const today = new Date();
            const dd = String(today.getDate()).padStart(2, '0');
            const mm = String(today.getMonth() + 1).padStart(2, '0');
            const yyyy = today.getFullYear();
            const formattedDate = `${dd}/${mm}/${yyyy}`;
            
            // Adicionar ao array de depósitos
            deposits.push({
                date: formattedDate,
                amount: amount,
                user: userName
            });
            
            // Atualizar total
            totalAmount += amount;
            
            // Atualizar interface
            updateProgress();
            updateHistory();
            
            // Limpar inputs
            amountInput.value = '';
            userNameInput.value = '';
        }
        
        // Função para editar objetivo
        function editGoal() {
            const modal = document.getElementById('goal-modal');
            modal.style.display = 'flex';
        }
        
        // Função para salvar novo objetivo
        function saveGoal() {
            const newGoalInput = document.getElementById('new-goal');
            const newGoal = parseFloat(newGoalInput.value);
            
            if (isNaN(newGoal) || newGoal <= 0) {
                alert('Por favor, insira um valor válido maior que zero.');
                return;
            }
            
            goalAmount = newGoal;
            updateProgress();
            
            // Fechar modal
            document.getElementById('goal-modal').style.display = 'none';
            newGoalInput.value = '';
        }
        
        // Função para limpar histórico
        function clearHistory() {
            if (confirm('Tem certeza que deseja limpar todo o histórico de depósitos?')) {
                deposits = [];
                totalAmount = 0;
                updateProgress();
                updateHistory();
            }
        }
        
        // Função para salvar uma nota
        function saveNote() {
            const noteInput = document.getElementById('note-input');
            const note = noteInput.value.trim();
            
            if (note === '') {
                alert('Por favor, escreva uma nota antes de salvar.');
                return;
            }
            
            // Salvar a nota no localStorage
            const notes = JSON.parse(localStorage.getItem('economizaKids_notes') || '[]');
            notes.push({
                text: note,
                date: new Date().toLocaleDateString('pt-BR')
            });
            localStorage.setItem('economizaKids_notes', JSON.stringify(notes));
            
            alert(`Nota salva: "${note}"`);
            noteInput.value = '';
        }
        
        // Função para verificar se o objetivo foi concluído
        function checkGoalCompletion() {
            if (totalAmount >= goalAmount) {
                // Abrir o modal de objetivo concluído se ainda não estiver aberto
                const modal = document.getElementById('goal-completed-modal');
                if (modal.style.display !== 'flex') {
                    modal.style.display = 'flex';
                }
            }
        }
        
        // Função para arquivar objetivo atual e criar um novo
        function archiveCurrentGoal() {
            const goalNameInput = document.getElementById('goal-name');
            const newGoalInput = document.getElementById('completed-new-goal');
            const goalName = goalNameInput.value.trim() || currentGoalName;
            const newGoal = parseFloat(newGoalInput.value);
            
            if (isNaN(newGoal) || newGoal <= 0) {
                alert('Por favor, insira um valor válido maior que zero para o novo objetivo.');
                return;
            }
            
            // Arquivar objetivo atual
            archivedGoals.push({
                name: currentGoalName,
                amount: goalAmount,
                achieved: totalAmount,
                completedAt: new Date().toLocaleDateString('pt-BR'),
                deposits: [...deposits]
            });
            
            // Configurar novo objetivo
            currentGoalName = goalName;
            goalAmount = newGoal;
            totalAmount = 0;
            deposits = [];
            
            // Atualizar interface
            updateProgress();
            updateHistory();
            updateArchivedGoals();
            
            // Fechar modal
            document.getElementById('goal-completed-modal').style.display = 'none';
            goalNameInput.value = '';
            newGoalInput.value = '';
            
            // Salvar tudo
            saveDataToLocalStorage();
        }
        
        // Função para exibir objetivos arquivados
        function updateArchivedGoals() {
            // Verificar se a seção de histórico de objetivos já existe
            let archivedSection = document.getElementById('archived-goals');
            
            if (!archivedSection && archivedGoals.length > 0) {
                // Criar a seção se não existir e houver objetivos arquivados
                archivedSection = document.createElement('section');
                archivedSection.className = 'section';
                archivedSection.id = 'archived-goals';
                archivedSection.innerHTML = `
                    <h2>Objetivos Concluídos</h2>
                    <div class="archived-actions">
                        <label class="select-all">
                            <input type="checkbox" id="select-all-goals"> Selecionar todos
                        </label>
                        <div class="action-buttons">
                            <button id="delete-selected-goals" class="small-button">Excluir Selecionados</button>
                            <button id="delete-all-goals" class="small-button warning">Excluir Todos</button>
                        </div>
                    </div>
                    <div class="archived-list" id="archived-goals-list"></div>
                `;
                
                // Adicionar como último elemento antes da seção avançado
                const advancedSection = document.getElementById('advanced');
                advancedSection.parentNode.insertBefore(archivedSection, advancedSection);
                
                // Adicionar ao menu de navegação
                const nav = document.querySelector('nav');
                const advancedLink = document.querySelector('nav a[href="#advanced"]');
                const archivedLink = document.createElement('a');
                archivedLink.href = '#archived-goals';
                archivedLink.textContent = 'Concluídos';
                nav.insertBefore(archivedLink, advancedLink);
                
                // Adicionar evento de clique para rolagem suave
                archivedLink.addEventListener('click', function(e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
                
                // Adicionar event listeners para os botões de ação
                document.getElementById('select-all-goals').addEventListener('click', toggleSelectAllGoals);
                document.getElementById('delete-selected-goals').addEventListener('click', deleteSelectedArchivedGoals);
                document.getElementById('delete-all-goals').addEventListener('click', deleteAllArchivedGoals);
            } else if (archivedSection && archivedGoals.length === 0) {
                // Se não houver mais objetivos arquivados, remover a seção
                archivedSection.remove();
                
                // Remover também o link de navegação
                const archivedLink = document.querySelector('nav a[href="#archived-goals"]');
                if (archivedLink) {
                    archivedLink.remove();
                }
                return;
            }
            
            // Se existir a seção e houver objetivos, atualizar a lista
            if (archivedSection && archivedGoals.length > 0) {
                const list = document.getElementById('archived-goals-list') || archivedSection.querySelector('.archived-list');
                list.innerHTML = '';
                
                archivedGoals.forEach((goal, index) => {
                    const item = document.createElement('div');
                    item.className = 'achievement archived-goal';
                    item.innerHTML = `
                        <div class="goal-header">
                            <label class="checkbox-container">
                                <input type="checkbox" class="goal-checkbox" data-index="${index}">
                                <span class="checkmark"></span>
                            </label>
                            <h3>${goal.name}</h3>
                        </div>
                        <p>Objetivo: ${formatCurrency(goal.amount)}</p>
                        <p>Alcançado: ${formatCurrency(goal.achieved)}</p>
                        <p>Data: ${goal.completedAt}</p>
                        <div class="goal-actions">
                            <button class="view-details" data-index="${index}">Ver Detalhes</button>
                            <button class="delete-goal" data-index="${index}">Excluir</button>
                        </div>
                    `;
                    list.appendChild(item);
                    
                    // Adicionar evento para ver detalhes
                    item.querySelector('.view-details').addEventListener('click', () => {
                        alert(`Objetivo: ${goal.name}\nValor: ${formatCurrency(goal.amount)}\nDepósitos: ${goal.deposits.length}\nData de conclusão: ${goal.completedAt}`);
                    });
                    
                    // Adicionar evento para excluir o objetivo
                    item.querySelector('.delete-goal').addEventListener('click', () => {
                        deleteArchivedGoal(index);
                    });
                });
                
                // Atualizar os event listeners para os botões de ação
                document.getElementById('select-all-goals').addEventListener('click', toggleSelectAllGoals);
                document.getElementById('delete-selected-goals').addEventListener('click', deleteSelectedArchivedGoals);
                document.getElementById('delete-all-goals').addEventListener('click', deleteAllArchivedGoals);
            }
        }
        
        // Adicionar função para excluir um objetivo arquivado específico
        function deleteArchivedGoal(index) {
            if (confirm('Tem certeza que deseja excluir este objetivo concluído?')) {
                archivedGoals.splice(index, 1);
                saveDataToLocalStorage();
                updateArchivedGoals();
            }
        }

        // Função para excluir todos os objetivos selecionados
        function deleteSelectedArchivedGoals() {
            const selectedCheckboxes = document.querySelectorAll('.goal-checkbox:checked');
            if (selectedCheckboxes.length === 0) {
                alert('Nenhum objetivo selecionado para excluir.');
                return;
            }

            if (confirm(`Tem certeza que deseja excluir ${selectedCheckboxes.length} objetivo(s) selecionado(s)?`)) {
                const indicesToDelete = Array.from(selectedCheckboxes).map(checkbox => 
                    parseInt(checkbox.getAttribute('data-index'))
                ).sort((a, b) => b - a); // Ordena em ordem decrescente para remover de trás para frente
                
                indicesToDelete.forEach(index => {
                    archivedGoals.splice(index, 1);
                });
                
                saveDataToLocalStorage();
                updateArchivedGoals();
            }
        }

        // Função para excluir todos os objetivos arquivados
        function deleteAllArchivedGoals() {
            if (confirm('Tem certeza que deseja excluir TODOS os objetivos concluídos? Esta ação não pode ser desfeita.')) {
                archivedGoals = [];
                saveDataToLocalStorage();
                updateArchivedGoals();
            }
        }

        // Função para selecionar/desselecionar todos os objetivos
        function toggleSelectAllGoals() {
            const mainCheckbox = document.getElementById('select-all-goals');
            const isChecked = mainCheckbox.checked;
            document.querySelectorAll('.goal-checkbox').forEach(checkbox => {
                checkbox.checked = isChecked;
            });
        }
        
        // Inicializar elementos e adicionar event listeners quando o DOM estiver carregado
        document.addEventListener('DOMContentLoaded', () => {
            // Carregar dados do localStorage
            loadDataFromLocalStorage();
            
            // Inicializar progresso
            updateProgress();
            updateHistory();
            updateArchivedGoals();
            
            // Event listeners para botões
            document.getElementById('add-deposit').addEventListener('click', addDeposit);
            document.getElementById('edit-goal').addEventListener('click', editGoal);
            document.getElementById('clear-history').addEventListener('click', clearHistory);
            document.getElementById('save-note').addEventListener('click', saveNote);
            document.getElementById('save-goal').addEventListener('click', saveGoal);
            document.getElementById('archive-goal').addEventListener('click', archiveCurrentGoal);
            document.getElementById('close-completed-modal').addEventListener('click', () => {
                document.getElementById('goal-completed-modal').style.display = 'none';
            });
            
            // Fechar modal
            document.querySelector('.close').addEventListener('click', () => {
                document.getElementById('goal-modal').style.display = 'none';
            });
            
            // Fechar modais ao clicar fora deles
            window.addEventListener('click', (event) => {
                const goalModal = document.getElementById('goal-modal');
                const completedModal = document.getElementById('goal-completed-modal');
                
                if (event.target === goalModal) {
                    goalModal.style.display = 'none';
                }
                
                if (event.target === completedModal) {
                    completedModal.style.display = 'none';
                }
            });
            
            // Suporte a navegação suave para links âncora
            document.querySelectorAll('nav a').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
            
            // Detectar gestos de toque para dispositivos móveis
            let touchStartX = 0;
            let touchEndX = 0;
            
            document.addEventListener('touchstart', e => {
                touchStartX = e.changedTouches[0].screenX;
            });
            
            document.addEventListener('touchend', e => {
                touchEndX = e.changedTouches[0].screenX;
                handleSwipe();
            });
            
            function handleSwipe() {
                // Swipe esquerda/direita para navegação entre seções
                const sections = ['#savings', '#history', '#achievements', '#advanced'];
                if (touchEndX < touchStartX - 100) {
                    // Swipe para esquerda - próxima seção
                    navigateToNextSection(sections, 1);
                }
                if (touchEndX > touchStartX + 100) {
                    // Swipe para direita - seção anterior
                    navigateToNextSection(sections, -1);
                }
            }
            
            function navigateToNextSection(sections, direction) {
                const currentScrollY = window.scrollY;
                let currentSectionIndex = -1;
                
                // Verificar qual é a seção atual
                for (let i = 0; i < sections.length; i++) {
                    const section = document.querySelector(sections[i]);
                    const rect = section.getBoundingClientRect();
                    if (rect.top <= 100 && rect.bottom >= 100) {
                        currentSectionIndex = i;
                        break;
                    }
                }
                
                if (currentSectionIndex !== -1) {
                    const targetIndex = (currentSectionIndex + direction + sections.length) % sections.length;
                    document.querySelector(sections[targetIndex]).scrollIntoView({ behavior: 'smooth' });
                }
            }
        });
        
        // Adicionar estilos para os novos elementos no head do documento
        const head = document.head;
        const styleElement = document.createElement('style');
        styleElement.textContent = `
            .archived-actions {
                display: flex;
                justify-content: space-between;
                align-items: center;
                margin-bottom: 1.5rem;
                flex-wrap: wrap;
                gap: 1rem;
            }
            
            .select-all {
                display: flex;
                align-items: center;
                gap: 0.5rem;
                cursor: pointer;
            }
            
            .goal-header {
                display: flex;
                align-items: center;
                gap: 1rem;
            }
            
            .checkbox-container {
                display: inline-block;
                position: relative;
                cursor: pointer;
                font-size: 16px;
                user-select: none;
            }
            
            .checkbox-container input {
                position: absolute;
                opacity: 0;
                cursor: pointer;
            }
            
            .checkmark {
                position: relative;
                height: 20px;
                width: 20px;
                background-color: #333;
                border: 2px solid var(--accent);
                border-radius: 4px;
            }
            
            .checkbox-container input:checked ~ .checkmark:after {
                content: "";
                position: absolute;
                display: block;
                left: 6px;
                top: 2px;
                width: 5px;
                height: 10px;
                border: solid var(--accent);
                border-width: 0 2px 2px 0;
                transform: rotate(45deg);
            }
            
            .goal-actions {
                display: flex;
                gap: 0.5rem;
                margin-top: 1rem;
            }
            
            .small-button {
                padding: 0.5rem 1rem;
                font-size: 0.9rem;
            }
            
            .warning {
                background: #ff3b30;
            }
            
            .warning:hover {
                background: #ff6b60;
            }
            
            .delete-goal {
                background: #ff3b30;
                color: white;
            }
            
            .delete-goal:hover {
                background: #ff6b60;
            }
        `;
        head.appendChild(styleElement);
    </script>
</body>
</html>
