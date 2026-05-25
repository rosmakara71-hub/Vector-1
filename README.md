<!DOCTYPE html>
<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>លំហាត់ស្តីពីវ៉ិចទ័រទីតាំង</title>
    <style>
        body {
            font-family: 'KHMER OS Battambang', 'Khmer OS', sans-serif;
            line-height: 1.8;
            background-color: #f4f7f6;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        h1 {
            color: #1a5276;
            text-align: center;
            border-bottom: 3px solid #2980b9;
            padding-bottom: 10px;
        }
        .lesson-summary {
            background-color: #ebf5fb;
            border-left: 5px solid #2980b9;
            padding: 15px;
            margin-bottom: 30px;
            border-radius: 4px;
        }
        .exercise {
            background: #fafafa;
            border: 1px solid #e0e0e0;
            padding: 15px 20px;
            margin-bottom: 20px;
            border-radius: 6px;
        }
        .exercise-title {
            font-weight: bold;
            color: #c0392b;
            margin-bottom: 10px;
        }
        .formula {
            display: block;
            text-align: center;
            font-weight: bold;
            margin: 10px 0;
            color: #2c3e50;
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

<div class="container">
    <h1>កម្រងលំហាត់៖ វ៉ិចទ័រទីតាំង និងការចែកអង្កត់</h1>

    <div class="lesson-summary">
        <h3>💡 រំលឹកវិធាន និងរូបមន្តគន្លឹះ៖</h3>
        <ul>
            <li><strong>វ៉ិចទ័រទីតាំង៖</strong> <span class="vector">OP</span> = <span class="vector">p</span> ជាវ៉ិចទ័រទីតាំងនៃចំណុច P ធៀបនឹងគល់ O។</li>
            <li><strong>ចំណុចចែកក្នុង C តាមផលធៀប m : n ៖</strong> 
                <span class="formula"><span class="vector">c</span> = (m<span class="vector">b</span> + n<span class="vector">a</span>) / (m + n)</span>
            </li>
            <li><strong>ចំណុចចែកក្រៅ D តាមផលធៀប m : n ៖</strong> 
                <span class="formula"><span class="vector">d</span> = (m<span class="vector">b</span> - n<span class="vector">a</span>) / (m - n)</span>
            </li>
        </ul>
    </div>

    <h2>✍️ ផ្នែកលំហាត់អនុវត្ត</h2>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ១ (កម្រិតដំបូង)</div>
        <p>គេមានពីរចំណុច A និង B ដែលមានវ៉ិចទ័រទីតាំងរៀងគ្នា <span class="vector">a</span> = (2, 4) និង <span class="vector">b</span> = (6, 8)។ ចូររកវ៉ិចទ័រទីតាំង <span class="vector">c</span> នៃចំណុច C ដែលចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប 1 : 1 (ចំណុចកណ្តាល)។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ២</div>
        <p>គេឲ្យវ៉ិចទ័រទីតាំងនៃចំណុច A គឺ <span class="vector">a</span> = (1, -3) និងចំណុច B គឺ <span class="vector">b</span> = (5, 9)។ ចូរគណនាវ៉ិចទ័រទីតាំង <span class="vector">c</span> នៃចំណុច C ដែលចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប m : n = 1 : 2។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៣</div>
        <p>ក្នុងលំហគំរូ គេមានចំណុច A(<span class="vector">a</span>) និង B(<span class="vector">b</span>) ដែល <span class="vector">a</span> = (3, 1, 4) និង <span class="vector">b</span> = (7, 6, -1)។ ចូររកកូអរដោនេនៃវ៉ិចទ័រទីតាំង <span class="vector">c</span> នៃចំណុច C ដែលចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប 3 : 2។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៤</div>
        <p>គេឲ្យចំណុច A និង B មានវ៉ិចទ័រទីតាំងរៀងគ្នា <span class="vector">a</span> = (-2, 5) និង <span class="vector">b</span> = (3, -5)។ ចូរស្វែងរកវ៉ិចទ័រទីតាំង <span class="vector">d</span> នៃចំណុច D ដែលចែកអង្កត់ AB ខាងក្រៅតាមផលធៀប m : n = 4 : 3។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៥</div>
        <p>គេមានពីរចំណុច A(2, -1, 3) និង B(5, 2, -3) នៅក្នុងលំហ។ ចូរគណនាកូអរដោនេនៃចំណុច D ដែលជាចំណុចចែកអង្កត់ AB ខាងក្រៅតាមផលធៀប 2 : 1។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៦</div>
        <p>គេឲ្យវ៉ិចទ័រទីតាំង <span class="vector">a</span> = (4, 2) និង <span class="vector">b</span> = (10, 8)។ ចំណុច P មួយចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប 2 : 1 ហើយចំណុច Q មួយទៀតចែកអង្កត់ AB ខាងក្រៅតាមផលធៀប 2 : 1 ដូចគ្នា។ ចូរគណនាវ៉ិចទ័រទីតាំងនៃចំណុច P និង Q។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៧ (លំហាត់បកស្រាយបញ្ច្រាស)</div>
        <p>គេមានចំណុច A(1, 2), B(7, 5) និងចំណុច C(3, transmissions មិនច្បាស់) ដែលមានវ៉ិចទ័រទីតាំង <span class="vector">c</span> = (3, 3)។ ដឹងថា C ជាចំណុចនៅលើអង្កត់ AB។ ចូររកផលធៀប m : n ដែលចំណុច C ចែកអង្កត់ AB ខាងក្នុង។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៨</div>
        <p>ផ្អែកលើរូបមន្តចែកខាងក្នុង <span class="vector">c</span> = (m<span class="vector">b</span> + n<span class="vector">a</span>) / (m + n)។ ចូរស្រាយបំភ្លឺថា បើសិនជា m = n (ផលធៀប 1 : 1) នោះចំណុច C គឺជាចំណុចកណ្តាលពិតប្រាកដនៃអង្កត់ AB ដែលមានវ៉ិចទ័រទីតាំង <span class="vector">c</span> = (<span class="vector">a</span> + <span class="vector">b</span>) / 2។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ៩</div>
        <p>គេមានត្រីកោណ ABC មួយដែលមានវ៉ិចទ័រទីតាំងនៃកំពូលនីមួយៗគឺ <span class="vector">a</span>, <span class="vector">b</span>, និង <span class="vector">c</span>។ ចំណុច M ជាចំណុចកណ្តាលនៃជ្រុង BC។ <br>
        ក. ចូររកវ៉ិចទ័រទីតាំង <span class="vector">m</span> នៃចំណុច M។<br>
        ខ. គេដឹងថាទីប្រជុំទម្ងន់ G នៃត្រីកោណ ABC ចែកមធ្យformat AM ខាងក្នុងតាមផលធៀប AG : GM = 2 : 1។ ចូរស្រាយបញ្ជាក់ថា វ៉ិចទ័រទីតាំងនៃទីប្រជុំទម្ងន់ G គឺ <span class="vector">g</span> = (<span class="vector">a</span> + <span class="vector">b</span> + <span class="vector">c</span>) / 3។</p>
    </div>

    <div class="exercise">
        <div class="exercise-title">លំហាត់ទី ១០ (កម្រិតខ្ពស់)</div>
        <p>គេឲ្យបីចំណុច A, B, និង C មិនរត់ត្រង់ជួរគ្នានៅក្នុងលំហ ដែលមានវ៉ិចទ័រទីតាំងរៀងគ្នា <span class="vector">a</span>, <span class="vector">b</span>, និង <span class="vector">c</span>។ ចំណុច P ចែកអង្កត់ AB ខាងក្នុងតាមផលធៀប 3 : 1 ហើយចំណុច Q ចែកអង្កត់ BC ខាងក្រៅតាមផលធៀប 3 : 2។ ចូរគណនាវ៉ិចទ័រទីតាំងនៃចំណុច P និង Q ជាអនុគមន៍នៃ <span class="vector">a</span>, <span class="vector">b</span>, និង <span class="vector">c</span>។</p>
    </div>

</div>

</body>
</html>
