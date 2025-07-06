# Data-Classification-and-Summarization-Using-IBM-Granite

# Nama Proyek

Zen Calc

## Daftar Isi
*   [Deskripsi Proyek](#description-project)
*   [Penggunaan Teknologi](#technologies-used)
*   [Fitur](#features)
*   [Set Up Aplikasi](#setup-instructions)
*   [Penjelasan AI Pendukung](#AI-support-explanation)

## Deskripsi Proyek

**Zen Calc** merupakan Aplikasi calculator ini adalah program sederhana yang dirancang untuk membantu pengguna melakukan operasi perhitungan matematika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian. Dibangun menggunakan bahasa pemrograman populer seperti Python atau JavaScript, aplikasi ini memiliki antarmuka yang intuitif dengan tombol angka dan operator yang mudah digunakan. Saat pengguna menekan tombol, input akan diproses melalui fungsi logika yang menangani setiap operasi aritmatika. Hasil perhitungan kemudian ditampilkan secara real-time pada layar. Selain itu, aplikasi ini dirancang ringan dan cepat, sehingga cocok dijalankan pada perangkat dengan spesifikasi rendah sekalipun. Dengan struktur kode yang modular, aplikasi ini juga mudah dikembangkan lebih lanjut untuk mendukung fitur lanjutan seperti perhitungan persentase, akar kuadrat, atau bahkan kalkulasi ilmiah.

## Pengunaan Teknologi
Teknologi dalam aplikasi ini menggunakan bahasa pemograman Java (HTML dan CSS)

## Fitur
Aplikasi kalkulator ini dibuat memiliki berbagai fitur yang dirancang untuk memberikan pengalaman pengguna yang baik dan fungsionalitas yang lengkap. Berikut adalah fitur-fitur utama dari aplikasi kalkulator ini:

1. **Operasi Dasar**: 
   - Penjumlahan (+)
   - Pengurangan (-)
   - Perkalian (×)
   - Pembagian (÷)

2. **Tombol Angka**: 
   - Tombol untuk angka 0-9
   - Tombol desimal (.)

3. **Clear dan Delete**:
   - Tombol "AC" untuk menghapus semua input dan mengatur ulang kalkulator.
   - Tombol "DEL" untuk menghapus angka terakhir yang dimasukkan.

4. **Tampilan yang Jelas**:
   - Display yang memisahkan operand sebelumnya dan operand saat ini.
   - Format angka dengan pemisah ribuan untuk kemudahan pembacaan.

5. **Responsive Design**:
   - Desain yang dapat menyesuaikan dengan berbagai ukuran layar, baik di desktop maupun perangkat mobile.

6. **Tampilan Eye-Friendly**:
   - Warna latar belakang dan tombol yang lembut dan tidak menyakitkan mata.
   - Tema gelap dan terang yang dapat diubah sesuai preferensi pengguna.

7. **Dukungan Keyboard**:
   - Pengguna dapat menggunakan keyboard untuk memasukkan angka dan operasi, termasuk tombol Enter untuk menghitung dan Backspace untuk menghapus.

8. **Animasi Tombol**:
   - Animasi sederhana saat tombol ditekan untuk meningkatkan pengalaman pengguna.

9. **Riwayat Operasi**:
   - Menampilkan operand sebelumnya di atas operand saat ini, sehingga pengguna dapat melihat operasi yang sedang dilakukan.

10. **Toggle Tema**:
    - Tombol untuk beralih antara mode gelap dan terang, memberikan fleksibilitas kepada pengguna untuk memilih tampilan yang mereka sukai.

Dengan fitur-fitur ini, aplikasi kalkulator ini dirancang untuk menjadi alat yang praktis dan mudah digunakan untuk melakukan perhitungan sehari-hari.

## AI Support Explanation

**ChatGPT**: ChatGPT adalah sebuah kecerdasan buatan (AI) berbasis pemrosesan bahasa alami (Natural Language Processing / NLP) yang dikembangkan oleh OpenAI. ChatGPT dirancang untuk dapat memahami, memproses, dan merespons bahasa manusia dengan cara yang alami dan kontekstual. 
   ChatGPT berfungsi sebagai media cerdas yang membantu menyediakan informasi dengan cepat dan mudah kepada penggunanya. Dengan memanfaatkan teknologi pemrosesan bahasa alami (Natural Language Processing), ChatGPT dapat memahami pertanyaan dalam bahasa manusia dan merespons dengan jawaban yang relevan. Ini membuatnya sangat berguna untuk menjawab berbagai macam pertanyaan, mulai dari topik umum seperti sains dan sejarah, hingga hal-hal praktis seperti tips karier, rekomendasi produk, atau penjelasan konsep sulit. Selain itu, ChatGPT juga dapat membantu membuat ringkasan teks, menyusun ide tulisan, bahkan melakukan simulasi percakapan untuk latihan komunikasi. Kemampuan adaptasinya menjadikan ChatGPT efektif sebagai alat digital untuk pendamping belajar, asisten kerja, maupun teman diskusi yang selalu siap memberikan informasi sesuai kebutuhan penggunanya hanya lewat percakapan teks — cepat, fleksibel, yang bisa diakses kapan saja.


**BLACKBOX AI** : Blackbox AI adalah sebuah platform kecerdasan buatan yang terutama dirancang untuk membantu developer dan programmer dalam menulis, mencari, dan memahami kode. Berbeda dengan ChatGPT yang lebih umum, Blackbox AI fokus pada konteks coding. Secara sederhana, Blackbox AI bisa disebut sebagai “asisten coding berbasis AI” yang dapat membaca, menganalisis, dan menghasilkan potongan kode dari berbagai bahasa pemrograman.

Kegunaan & manfaat Blackbox AI bagi penggunanya:

1. Autocompletion & code generation: Blackbox AI dapat melengkapi atau bahkan menghasilkan potongan kode secara otomatis berdasarkan perintah atau potongan kode yang sudah ditulis, sehingga mempercepat proses coding.

2. Code search lintas repositori: Memungkinkan pengguna mencari fungsi atau pola kode tertentu dari berbagai sumber terbuka (open-source) secara cepat, tanpa harus membuka repositori satu per satu.

3. Membantu memahami kode: Blackbox AI dapat membantu menjelaskan baris kode yang kompleks atau dokumentasi fungsi tertentu, cocok bagi pemula maupun profesional yang sedang mempelajari codebase besar.

4. Debugging & menemukan bug: Dengan kecerdasan buatannya, Blackbox AI bisa membantu mengidentifikasi kesalahan umum dalam kode serta menyarankan perbaikan.

5. Meningkatkan efisiensi kerja developer: Karena banyak tugas manual seperti mencari snippet, memperbaiki error, atau menulis boilerplate code dapat diotomatisasi, programmer jadi bisa fokus pada logika bisnis dan fitur utama aplikasi mereka.


## SetUp Aplikasi

Penginstalan aplikasi sederhana Kalkulator

```bash

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Eye-Friendly Calculator</title>
    <style>
        :root {
            --primary-color: #6c5ce7;
            --secondary-color: #a29bfe;
            --bg-color: #f8f9fa;
            --display-color: #ffffff;
            --btn-color: #e8e8e8;
            --btn-hover: #d3d3d3;
            --operator-color: #74b9ff;
            --operator-hover: #0984e3;
            --equal-color: #00b894;
            --equal-hover: #009972;
            --text-dark: #2d3436;
            --text-light: #636e72;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .calculator {
            width: 100%;
            max-width: 340px;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            background: linear-gradient(145deg, #ffffff, #ececec);
        }

        .display-container {
            padding: 20px;
            background-color: var(--display-color);
            text-align: right;
        }

        .previous-operand {
            font-size: 1.2rem;
            color: var(--text-light);
            height: 24px;
            overflow: hidden;
        }

        .current-operand {
            font-size: 2.5rem;
            color: var(--text-dark);
            margin-top: 10px;
            word-break: break-all;
        }

        .buttons-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 10px;
            padding: 20px;
        }

        button {
            border: none;
            outline: none;
            padding: 15px;
            font-size: 1.2rem;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.2s ease;
            font-weight: 500;
            color: var(--text-dark);
            background-color: var(--btn-color);
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        button:active {
            transform: translateY(0);
            box-shadow: none;
        }

        .span-two {
            grid-column: span 2;
        }

        .operator {
            background-color: var(--operator-color);
            color: white;
        }

        .operator:hover {
            background-color: var(--operator-hover);
        }

        .equals {
            background-color: var(--equal-color);
            color: white;
        }

        .equals:hover {
            background-color: var(--equal-hover);
        }

        .ac, .del {
            background-color: #fdcb6e;
            color: white;
        }

        .ac:hover, .del:hover {
            background-color: #e17055;
        }

        /* Dark mode toggle */
        .theme-toggle {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: var(--btn-color);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        /* Responsive adjustments */
        @media (max-width: 400px) {
            .buttons-grid {
                grid-gap: 8px;
                padding: 15px;
            }
            button {
                padding: 12px;
                font-size: 1rem;
            }
        }

        @media (max-height: 600px) {
            body {
                padding: 10px;
            }
            .calculator {
                max-width: 300px;
            }
        }
    </style>
</head>
<body>
    <div class="theme-toggle" id="themeToggle">
        ☀️
    </div>
    <div class="calculator">
        <div class="display-container">
            <div class="previous-operand" id="previousOperand"></div>
            <div class="current-operand" id="currentOperand">0</div>
        </div>
        <div class="buttons-grid">
            <button class="ac span-two">AC</button>
            <button class="del">DEL</button>
            <button class="operator">÷</button>
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button class="operator">×</button>
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button class="operator">-</button>
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="operator">+</button>
            <button>.</button>
            <button>0</button>
            <button class="equals span-two">=</button>
        </div>
    </div>

    <script>
        class Calculator {
            constructor(previousOperandTextElement, currentOperandTextElement) {
                this.previousOperandTextElement = previousOperandTextElement;
                this.currentOperandTextElement = currentOperandTextElement;
                this.clear();
            }

            clear() {
                this.currentOperand = '0';
                this.previousOperand = '';
                this.operation = undefined;
                this.resetAfterNextOperation = false;
            }

            delete() {
                if (this.currentOperand.length === 1) {
                    this.currentOperand = '0';
                } else if (this.currentOperand !== '0') {
                    this.currentOperand = this.currentOperand.slice(0, -1);
                }
            }

            appendNumber(number) {
                if (this.resetAfterNextOperation) {
                    this.currentOperand = number;
                    this.resetAfterNextOperation = false;
                    return;
                }
                
                if (number === '.' && this.currentOperand.includes('.')) return;
                if (this.currentOperand === '0' && number !== '.') {
                    this.currentOperand = number;
                } else {
                    this.currentOperand = this.currentOperand + number;
                }
            }

            chooseOperation(operation) {
                if (this.currentOperand === '') return;
                if (this.previousOperand !== '') {
                    this.compute();
                }
                this.operation = operation;
                this.previousOperand = this.currentOperand;
                this.currentOperand = '';
            }

            compute() {
                let computation;
                const prev = parseFloat(this.previousOperand);
                const current = parseFloat(this.currentOperand);
                if (isNaN(prev) || isNaN(current)) return;

                switch (this.operation) {
                    case '+':
                        computation = prev + current;
                        break;
                    case '-':
                        computation = prev - current;
                        break;
                    case '×':
                        computation = prev * current;
                        break;
                    case '÷':
                        computation = prev / current;
                        break;
                    default:
                        return;
                }

                this.currentOperand = computation.toString();
                this.operation = undefined;
                this.previousOperand = '';
                this.resetAfterNextOperation = true;
            }

            getDisplayNumber(number) {
                const stringNumber = number.toString();
                const integerDigits = parseFloat(stringNumber.split('.')[0]);
                const decimalDigits = stringNumber.split('.')[1];
                let integerDisplay;
                if (isNaN(integerDigits)) {
                    integerDisplay = '';
                } else {
                    integerDisplay = integerDigits.toLocaleString('en', {
                        maximumFractionDigits: 0
                    });
                }
                if (decimalDigits != null) {
                    return `${integerDisplay}.${decimalDigits}`;
                } else {
                    return integerDisplay;
                }
            }

            updateDisplay() {
                this.currentOperandTextElement.innerText = this.getDisplayNumber(this.currentOperand);
                if (this.operation != null) {
                    this.previousOperandTextElement.innerText = 
                        `${this.getDisplayNumber(this.previousOperand)} ${this.operation}`;
                } else {
                    this.previousOperandTextElement.innerText = '';
                }
            }
        }

        // Initialize calculator
        const numberButtons = document.querySelectorAll('[class*="number"]');
        const operationButtons = document.querySelectorAll('.operator');
        const equalsButton = document.querySelector('.equals');
        const deleteButton = document.querySelector('.del');
        const allClearButton = document.querySelector('.ac');
        const previousOperandTextElement = document.querySelector('#previousOperand');
        const currentOperandTextElement = document.querySelector('#currentOperand');

        const calculator = new Calculator(previousOperandTextElement, currentOperandTextElement);

        // Event listeners for buttons
        document.querySelectorAll('button:not(.operator):not(.equals):not(.ac):not(.del):not(.span-two)').forEach(button => {
            button.addEventListener('click', () => {
                calculator.appendNumber(button.innerText);
                calculator.updateDisplay();
            });
        });

        operationButtons.forEach(button => {
            button.addEventListener('click', () => {
                calculator.chooseOperation(button.innerText);
                calculator.updateDisplay();
            });
        });

        equalsButton.addEventListener('click', () => {
            calculator.compute();
            calculator.updateDisplay();
        });

        allClearButton.addEventListener('click', () => {
            calculator.clear();
            calculator.updateDisplay();
        });

        deleteButton.addEventListener('click', () => {
            calculator.delete();
            calculator.updateDisplay();
        });

        // Theme toggle functionality
        const themeToggle = document.getElementById('themeToggle');
        themeToggle.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            if (document.body.classList.contains('dark-mode')) {
                themeToggle.innerText = '🌙';
                document.documentElement.style.setProperty('--primary-color', '#4834d4');
                document.documentElement.style.setProperty('--secondary-color', '#686de0');
                document.documentElement.style.setProperty('--bg-color', '#2c3e50');
                document.documentElement.style.setProperty('--display-color', '#34495e');
                document.documentElement.style.setProperty('--btn-color', '#4a5568');
                document.documentElement.style.setProperty('--btn-hover', '#2d3748');
                document.documentElement.style.setProperty('--text-dark', '#f5f5f5');
                document.documentElement.style.setProperty('--text-light', '#d1d5db');
            } else {
                themeToggle.innerText = '☀️';
                document.documentElement.style.setProperty('--primary-color', '#6c5ce7');
                document.documentElement.style.setProperty('--secondary-color', '#a29bfe');
                document.documentElement.style.setProperty('--bg-color', '#f8f9fa');
                document.documentElement.style.setProperty('--display-color', '#ffffff');
                document.documentElement.style.setProperty('--btn-color', '#e8e8e8');
                document.documentElement.style.setProperty('--btn-hover', '#d3d3d3');
                document.documentElement.style.setProperty('--text-dark', '#2d3436');
                document.documentElement.style.setProperty('--text-light', '#636e72');
            }
        });

        // Keyboard support
        document.addEventListener('keydown', (e) => {
            if ((e.key >= 0 && e.key <= 9) || e.key === '.') {
                calculator.appendNumber(e.key);
                calculator.updateDisplay();
            } else if (e.key === '+' || e.key === '-' || e.key === '*' || e.key === '/') {
                const operationMap = { '*': '×', '/': '÷' };
                calculator.chooseOperation(operationMap[e.key] || e.key);
                calculator.updateDisplay();
            } else if (e.key === 'Enter' || e.key === '=') {
                calculator.compute();
                calculator.updateDisplay();
            } else if (e.key === 'Escape') {
                calculator.clear();
                calculator.updateDisplay();
            } else if (e.key === 'Backspace') {
                calculator.delete();
                calculator.updateDisplay();
            }
        });
    </script>
</body>
</html>

