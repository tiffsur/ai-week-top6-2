# 6 ИИ-новинок из ролика

Ссылки на всё из ролика. Данные на 23.10.2026.

**1. DeepSeek V4.1-Flash-1017** — открытые веса, лицензия MIT. Смесь экспертов: 552 млрд параметров в основе, на шаге генерации работают 16 млрд, контекст до миллиона токенов. По таблице DeepSeek обходит GLM-5.3 и GPT-5.6 Sol в пяти тестах из ролика (Terminal-Bench 4.0, DeepSWE v1.1, ProgramBench, Automation-Bench, Apex Bench). Бесплатны веса и чат, API платный.
https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017
Поиск и загрузка страниц в API: https://api-docs.deepseek.com/news/news261017

**2. Locally Uncensored** — одно бесплатное приложение: чат, картинки, видео и агент для кода. В локальном режиме всё работает на вашем компьютере, без Docker, терминала и конфигов. Windows 10/11 и Linux, для Mac на Apple Silicon — бета. AGPL-3.0.
https://github.com/PurpleDoubleD/locally-uncensored

**3. Gemini 4 Argon (Google)** — флагманская модель Google для длинных задач по коду и агентов, контекст 1 048 576 токенов. В API — платно, бесплатного уровня нет; в приложении Gemini — по подписке Pro и Ultra.
https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-argon/
Документация: https://ai.google.dev/gemini-api/docs/models/gemini-4-argon

**4. Beam (Reflection AI)** — открытые веса, Apache-2.0. 501 млрд параметров, из них 23 млрд активных. По данным Reflection — около 80% в Terminal-Bench 2.1 и примерно втрое меньше токенов, чем у GLM-5.2.
https://huggingface.co/reflection/Beam-1.0-501B-A23B

**5. PentAGI** — открытая команда ИИ-агентов для проверки ваших собственных систем на взлом: описываете цель обычными словами, агенты планируют работу, запускают nmap, Metasploit и sqlmap в изолированной песочнице Docker и отдают отчёт. MIT. Проверяйте только свои системы или те, на которые есть разрешение.
https://github.com/vxcontrol/pentagi

**6. SANA-WM (NVIDIA)** — открытая модель мира на 2,6 млрд параметров: по первому кадру, тексту и траектории камеры генерирует минуту видео в 720p, и камера идёт по заданной вами траектории. По документации NVIDIA — на одной видеокарте (замеры на H100).
https://nvlabs.github.io/Sana/docs/sana_wm/
Код: https://github.com/NVlabs/Sana (Apache-2.0)

Сравнения моделей — замеры самих авторов, не независимые тесты.
