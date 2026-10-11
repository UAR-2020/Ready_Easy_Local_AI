# Multilanguage MANUAL Local AstraLinux AI
[![en](https://img.shields.io/badge/Lang-Ru-red.svg)](https://github.com/UAR-2020/Ready_Easy_Local_AI/blob/main/Ready_Easy_Local_AI_ru.pdf)
[![pt-br](https://img.shields.io/badge/Lang-En-blue.svg)](https://github.com/UAR-2020/Ready_Easy_Local_AI/blob/main/Ready_Easy_Local_AI_en.pdf)

Выберите РУКОВОДСТВО с вашей версией языкового оформления [Lang|Ru]  /  Select the MANUAL with your version of the language design [Lang|En]  

+ Lazy, page 11 of the manual (deployment) / Ленивым, на страницу 11 мануала (развертывание)
+ Tested on Astra Linux 1.7.6 (Debian 10) OS / Тестировалось в ОС Astra Linux 1.7.6  (Debian 10)
---

# Ready Simple Local Artificial Intelligence [AI] on Astra Linux (Debian/Ubuntu)
  + Deploying AI via Ollama and OpenWebUI Docker containers from a ready‑made set of archives and configurations. Create set
# Готовый Простой Локальный Искусственный Интеллект [ИИ] на Astra Linux (Debian/Ubuntu)
  + Развертывание ИИ через докеры Ollama и OpenWebUI из готового набора архивов и конфигураций. Создание набора

# EN
The provided Ollama configurations implies loading, using, and unloading the model after its use. 
This is done to enable equal access for all users on the local network via the URL http://your-real-IP:3050 and to allow them 
to access it one by one without increasing the load on the video adapter (to avoid exceeding VRAM limits). 
Ollama waits for the model to be released after generation for a specific user, then responds to another user; in this process, 
the loading and subsequent unloading a different selected model (in the OpenWebUI interface, 
this will be displayed as a generation delay during shared access). 
This won’t meet the “warm‑up” requirements, but it will be rational. Authorization is disabled. 
This is a workhorse on a dedicated server in the local network. Just for deployment and use. 
It helps me with everyday scripting and other issues in an LAN without the Internet

# RU
Предоставленная конфигурация Ollama  подразумевают загрузку, использование и выгрузку модели после её использования. 
Это сделано для возможности равноправного доступа всех пользователей локальной сети по адресу URL http://ваш-реальный-IP:3050 и их поочередного доступа 
без увеличения нагрузки на видеоадаптер (чтобы не выйти за пределы VRAM).  
Ollama ожидает высвобождения после генерации определенному пользователю, затем отвечает другому, 
при этом осуществляется загрузка и последующая выгрузка выбранной модели (в интерфейсе OpenWebUI,
это будет отображаться в виде задержки генерации при совместном доступе). 
Это не будет удовлетворять требованиям "прогрева", но будет рационально. Авторизация отключена. 
Это рабочая лошадка на выделенном сервере в локальной сети. Просто для развертывания и применения. 
Мне это помогает в повседневном написании скриптов и прочих вопросах в ЛВС без Интернета

![alt text](https://github.com/UAR-2020/Ready_Easy_Local_AI/blob/main/Easy_local_AI.png?raw=true)

+ About the purpose, models and settings of Ollama and OpenWebUI [О предназначении, моделях и настройках Ollama и OpenWebUI]:
  https://ollama.com                                                        
  https://docs.ollama.com                                                 
  https://github.com/ollama/ollama                                   
  https://github.com/ollama/ollama/tree/main/docs
  https://openwebui.com/        
  https://docs.openwebui.com
  https://github.com/open-webui/open-webui
  
# Link to the ready‑made set of AI components [Ссылка на готовый набор компонентов ИИ]:
+ Download all the components (39 GB) for the manual or create what is needed based on it / Скачайте все компоненты (39Gb) для мануала или создайте необходимое по нему
#  https://files.sberdisk.ru/s/KV0SZt26hVJKXLL
  Link availability is not guaranteed / Доступность ссылки не гарантируется

---

# Добро пожаловать на обсуждения!  /  Welcome to discussions!  

https://github.com/UAR-2020/Ready_Easy_Local_AI/discussions

To copy configurations, it is recommended to use the RU version of the documentation (download manual)

Для для копирования конфигураций рекомендуется использовать RU версию документации (скачайте мануал)





