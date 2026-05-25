<!DOCTYPE html>
<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>លំហាត់ជ្រើសរើសចម្លើយ - វ៉ិចទ័រទីតាំង</title>
    <style>
        body {
            font-family: 'KHMER OS Battambang', 'Khmer OS', sans-serif;
            line-height: 1.8;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .quiz-container {
            max-width: 700px;
            margin: 0 auto;
            background: #ffffff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        }
        h1 {
            color: #2c3e50;
            text-align: center;
            border-bottom: 3px solid #3498db;
            padding-bottom: 15px;
        }
        .question-box {
            background: #fff;
            border: 1px solid #e2e8f0;
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 8px;
        }
        .question-text {
            font-weight: bold;
            font-size: 1.1em;
            color: #2c3e50;
            margin-bottom: 15px;
        }
        .options-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .option-item {
            margin-bottom: 10px;
        }
        .option-item label {
            display: block;
            padding: 10px 15px;
            background: #f8fafc;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.2s;
        }
        .option-item label:hover {
            background: #e2e8f0;
        }
        .option-item input[type="radio"] {
            margin-right: 10px;
        }
        .btn-submit {
            display: block;
            width: 100%;
            background: #3498db;
            color: #fff;
            border: none;
            padding: 12px;
            font-size: 1.1em;
            font-family: inherit;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.2s;
        }
        .btn-submit:hover {
            background: #2980b9;
        }
        .result-box {
            margin-top: 15px;
            padding: 10px 15px;
            border-radius: 6px;
            font-weight: bold;
            display: none;
        }
        .correct {
            background-color: #d1fae5;
            color: #065f46;
            border: 1px solid #a7f3d0;
        }
        .incorrect {
            background-color: #fee2e2;
            color: #991b1b;
            border: 1px solid #fecaca;
        }
        .vector {
            position: relative;
            display: inline-block;
        }
        .vector::after {
            content: "→";
            position: absolute;
            top: -12px;
            left: 0;
            width: 100%;
            text-align: center;
            font-size: 0.8em;
        }
    </style>
</head>
<body>

<div class="quiz-container">
    <h1>📝 លំនាំលំហាត់ជ្រើសរើសចម្លើយ (វ៉ិចទ័រទីតាំង)</h1>
    
    <form id="quizForm">
        <div class="question-box" id="q1-box">
            <div class="question-text">សំណួរទី ១៖ បើ <span class="vector">OP</span> = <span class="vector">p</span> ជាវ៉ិចទ័រទីតាំងនៃចំណុច P នោះចំណុច O ហៅថាអ្វី?</div>
            <ul class="options-list">
                <li class="option-item"><label><input type="radio" name="q1" value="A"> A. ចំណុចចល័ត</label></li>
                <li class="option-item"><label><input type="radio" name="q1" value="B"> B. ចំណុចគល់ (ឬចំណុចនឹង)</label></li>
                <li class="option-item"><label><input type="radio" name="q1" value="C"> C. វ៉ិចទ័រទីតាំង</label></li>
                <li class="option-item"><label><input type="radio" name="q1" value="D"> D. អង្កត់ផ្ចិត</label></li>
            </ul>
            <div class="result-box" id="r1"></div>
        </div>

        <div class="question-box" id="q2-box">
            <div class="question-text">សំណួរទី ២៖ រូបមន្តវ៉ិចទ័រទីតាំង <span class="vector">c</span> នៃចំណុច C ដែលចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប m : n គឺ៖</div>
            <ul class="options-list">
                <li class="option-item"><label><input type="radio" name="q2" value="A"> A. <span class="vector">c</span> = (m<span class="vector">b</span> + n<span class="vector">a</span>) / (m + n)</label></li>
                <li class="option-item"><label><input type="radio" name="q2" value="B"> B. <span class="vector">c</span> = (m<span class="vector">b</span> - n<span class="vector">a</span>) / (m - n)</label></li>
                <li class="option-item"><label><input type="radio" name="q2" value="C"> C. <span class="vector">c</span> = (m<span class="vector">a</span> + n<span class="vector">b</span>) / (m + n)</label></li>
                <li class="option-item"><label><input type="radio" name="q2" value="D"> D. <span class="vector">c</span> = (m<span class="vector">b</span> + n<span class="vector">a</span>) / (m - n)</label></li>
            </ul>
            <div class="result-box" id="r2"></div>
        </div>

        <div class="question-box" id="q3-box">
            <div class="question-text">សំណួរទី ៣៖ បើចំណុច C គឺជាចំណុចកណ្តាលនៃអង្កត់ AB នោះវ៉ិចទ័រទីតាំង <span class="vector">c</span> ស្មើនឹង៖</div>
            <ul class="options-list">
                <li class="option-item"><label><input type="radio" name="q3" value="A"> A. <span class="vector">a</span> + <span class="vector">b</span></label></li>
                <li class="option-item"><label><input type="radio" name="q3" value="B"> B. (<span class="vector">a</span> - <span class="vector">b</span>) / 2</label></li>
                <li class="option-item"><label><input type="radio" name="q3" value="C"> C. (<span class="vector">a</span> + <span class="vector">b</span>) / 2</label></li>
                <li class="option-item"><label><input type="radio" name="q3" value="D"> D. 2(<span class="vector">a</span> + <span class="vector">b</span>)</label></li>
            </ul>
            <div class="result-box" id="r3"></div>
        </div>

        <div class="question-box" id="q4-box">
            <div class="question-text">សំណួរទី ៤៖ គេឲ្យ <span class="vector">a</span> = (2, 3) និង <span class="vector">b</span> = (4, 7)។ រកវ៉ិចទ័រទីតាំងនៃចំណុចកណ្តាល C នៃអង្កត់ AB។</div>
            <ul class="options-list">
                <li class="option-item"><label><input type="radio" name="q4" value="A"> A. (6, 10)</label></li>
                <li class="option-item"><label><input type="radio" name="q4" value="B"> B. (3, 5)</label></li>
                <li class="option-item"><label><input type="radio" name="q4" value="C"> C. (1, 2)</label></li>
                <li class="option-item"><label><input type="radio" name="q4" value="D"> D. (3, 4)</label></li>
            </ul>
            <div class="result-box" id="r4"></div>
        </div>

        <div class="question-box" id="q5-box">
            <div class="question-text">សំណួរទី ៥៖ រូបមន្តវ៉ិចទ័រទីតាំង <span class="vector">d</span> នៃចំណុច D ដែលចែកអង្កត់ AB ខាងក្រៅតាមផលធៀប m : n គឺ៖</div>
            <ul class="options-list">
                <li class="option-item"><label><input type="radio" name="q5" value="A"> A. <span class="vector">d</span> = (m<span class="vector">b</span> + n<span class="vector">a</span>) / (m + n)</label></li>
                <li class="option-item"><label><input type="radio" name="q5" value="B"> B. <span class="vector">d</span> = (m<span class="vector">b</span> - n<span class="vector">a</span>) / (m - n)</label></li>
                <li class="option-item"><label><input type="radio" name="q5" value="C"> C. <span class="vector">d</span> = (n<span class="vector">a</span> - m<span class="vector">b</span>) / (m - n)</label></li>
                <li class="option-item"><label><input type="radio" name="q5" value="D"> D. <span class="vector">d</span> = (m<span class="vector">b</span> - n<span class="vector">a</span>) / (m + n)</label></li>
            </ul>
            <div class="result-box" id="r5"></div>
        </div>

        <button type="button" class="btn-submit" onclick="checkAnswers()">ផ្ទៀងផ្ទាត់ចម្លើយ</button>
    </form>
</div>

<script>
    function checkAnswers() {
        // គន្លឹះចម្លើយត្រឹមត្រូវ
        const answers = {
            q1: "B",
            q2: "A",
            q3: "C",
            q4: "B",
            q5: "B"
        };

        // ពន្យល់ចម្លើយនីមួយៗ
        const explanations = {
            q1: "ត្រឹមត្រូវ! ផ្អែកតាមមេរៀន O ជាចំណុចនឹង ឬហៅថាចំណុចគល់។",
            q2: "ត្រឹមត្រូវ! នេះជារូបមន្តចែកខាងក្នុង។",
            q3: "ត្រឹមត្រូវ! កាលណា m=n នាំឲ្យរូបមន្តក្លាយជា (a + b) / 2។",
            q4: "ត្រឹមត្រូវ! យកកូអរដោនេបូកបញ្ចូលគ្នា រួចចែកនឹង ២៖ ((2+4)/2, (3+7)/2) = (3, 5)។",
            q5: "ត្រឹមត្រូវ! នេះជារូបមន្តចែកខាងក្រៅដែលមានសញ្ញាដក (-)"
        };

        for (let i = 1; i <= 5; i++) {
            const questionName = 'q' + i;
            const resultBox = document.getElementById('r' + i);
            const selectedOption = document.querySelector(`input[name="${questionName}"]:checked`);

            resultBox.style.display = "block";

            if (!selectedOption) {
                resultBox.className = "result-box incorrect";
                resultBox.innerHTML = "សូមជ្រើសរើសចម្លើយមួយ!";
            } else if (selectedOption.value === answers[questionName]) {
                resultBox.className = "result-box correct";
                resultBox.innerHTML = "✨ " + explanations[questionName];
            } else {
                resultBox.className = "result-box incorrect";
                resultBox.innerHTML = "❌ ខុសហើយ! ចម្លើយត្រឹមត្រូវគឺគឺ " + answers[questionName];
            }
        }
    }
</script>

</body>
</html>
