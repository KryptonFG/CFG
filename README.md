# CFG
config file for cs2

crosshair - [https://github.com/T1ckbase/cs2-rainbow-crosshair]

Command
*violence_hblood "0"* - Controls whether or not human blood effects are shown in the game. Контролирует, будут ли в игре отображаться эффекты человеческой крови.
*cl_use_opens_buy_menu "0"* - This console command chooses whether or not you can use the "+use" key (usually E) when in the buy zone to open the buy menu. Эта консольная команда выбирает, можете ли вы использовать клавишу «+use» (обычно E) в зоне покупки, чтобы открыть меню покупки.
*cl_predict_body_shot_fx "0"* - Predicting body hits. Прогнозирование ударов по корпусу.
*cl_predict_head_shot_fx "0"* - Predicting head hits. Прогнозирование ударов головой.
*cl_predict_kill_ragdolls "1"* - Predicting ragdolls. Предсказание падение трупов.
*engine_low_latency_sleep_after_client_tick "1"* - Adjusts the behavior of low latency mode by changing the timing of the sleep function in relation to the client's simulation when r_low_latency is enabled. Регулирует поведение режима низкой задержки путем изменения времени функции сна по отношению к клиентской симуляции, если включено.r_low_latency
*engine_no_focus_sleep "0"* - This command will disable the sleeping of the engine when CS:GO is not an active window (e.g. when tabbed out). This will mean your FPS remains stable even when tabbed out. Эта команда отключит спящий режим движка, когда окно CS:GO неактивно (например, при закрытой вкладке). Это означает, что ваш FPS останется стабильным даже при закрытой вкладке.
*r_low_latency "1"* - For command engine_low_latency_sleep_after_client_tick. Для работы команды engine_low_latency_sleep_after_client_tick
*fps_max "0"* - Your desired FPS cap. Your FPS will not go above this number. Set to 0 to remove FPS cap. Желаемый предел FPS. FPS не будет превышать это значение. Установите 0, чтобы снять ограничение FPS.
*fps_max_ui "83"* - Maximum frame rate for the game UI. 0 for no limit. Максимальная частота кадров для игрового интерфейса. 0 — без ограничений.
*fps_max_tools "83"* - The maximum number of frames per second to be displayed in tools mode when the game window is not in focus. Setting this to 0 removes the limit. Максимальное количество кадров в секунду, отображаемых в режиме «Инструменты», когда окно игры не в фокусе. Установка значения 0 снимает ограничение.
*func_break_max_pieces "0"* - If the value is 0, there will be no garbage on the map. При значении 0 на карте не будет мусора.
*mm_dedicated_search_maxping "70"* - The maximum ping of a server you join. The lower you set this, the less laggy your matches might be, but it usually increases the time it takes to find a game. Максимальный пинг сервера, к которому вы подключаетесь. Чем ниже этот параметр, тем меньше задержек будет в матчах, но обычно это увеличивает время поиска игры.
*net_client_steamdatagram_enable_override "-1"* Turning it off helps if you have packet loss but it highers your ping. Отключение помогает, если у вас есть потеря пакетов, но повышает ваш пинг.
*mm_session_search_qos_timeout "3"* 
*lobby_default_privacy_bits2 "0"* - The setting for lobby privacy permissions. Настройка разрешений на конфиденциальность в лобби.
*r_fullscreen_gamma "2"* - The gamma value to set for fullscreen modes. A lower value makes the screen brighter, and a higher value makes it darker. Значение гаммы для полноэкранных режимов. Чем ниже значение, тем ярче экран, чем выше — темнее.
*rate "786432"* - Your desired network rate in bytes per second. 786432 - unrestricted. Желаемая скорость сети в байтах в секунду. 786432 - без ограничений. 
*spec_replay_autostart "0"* - Automatic Killer Replay. Автоматический повтор смерти.
*mp_autokick "0"* - This command would disable the auto kick feature. Эта команда отключит функцию автоматического кикка.
*cl_join_advertise "2"* - Lets your friends join the community server you are playing on without an invitation. Позволяет вашим друзьям присоединиться к серверу сообщества, на котором вы играете, без приглашения.
*cl_silencer_mode "1"* - Enables the silencer mode, allowing players to attach or detach silencers. Включает режим глушителя, позволяя игрокам прикреплять или отсоединять глушители.
*voice_always_sample_mic "1"* - Enables continuous sampling of the microphone to prevent hang or stall. Обеспечивает непрерывную запись сигнала с микрофона для предотвращения зависаний и сбоев.
*voice_threshold "300"* - This command would make your microphone activate when there is very little volume. This can fix issues if your voice isn't being picked up by voice activation. Эта команда активирует микрофон при очень низкой громкости. Это может решить проблемы, если голосовая активация не распознаёт ваш голос.
*ui_setting_advertiseforhire_auto "0"* - Disables automatic advertisement for invites. Отключает автоматическую рассылку приглашений для всех.
*cl_buywheel_donate_key "1"* - Determines whether a specific key is set for donations in the buy menu or not. Определяет, установлена ​​ли определенная клавиша для покупки другу в меню покупки или нет.
