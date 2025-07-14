gg.setVisible(true)

function menu()
    gg.clearResults()  -- Очищаем результаты
    active = 0

    -- Получаем информацию о процессе
    local info = gg.getTargetInfo()
    local packageName = info and info.packageName or "Неизвестный процесс"
    local architecture = info and (info.architecture == "arm64" and "64-бит" or "32-бит") or "Неизвестная архитектура"

    -- Формируем заголовок с выравниванием по центру
    local title = "Процесс : " .. packageName
    local centeredTitle = string.rep(" ", (30 - #title) / 2) .. title  -- Центрируем заголовок

    -- Получаем текущее время в формате ЧЧ:ММ и дату в формате ДД.ММ.ГГГГ
    local currentTime = os.date("%H:%M")
    local currentDate = os.date("%d.%m.%Y")
    
    -- Формируем строку с датой и временем
    local dateTimeLine = string.rep(" ", (30 - #("Дᴀᴛᴀ: " .. currentDate .. " Вᴩᴇʍя : " .. currentTime)) / 2) .. "Дᴀᴛᴀ: " .. currentDate .. " Вᴩᴇʍя : " .. currentTime  -- Центрируем дату и время

    -- Формируем строку с архитектурой
   
     gg.clearResults()  -- Очищаем результаты
    local main = gg.choice({        
        " 👨 | Пᴇᴩᴄᴏнᴀж | 👨 ",
        " 🚗 | Аʙᴛᴏʍᴏбиᴧь  | 🚗", 
        " 👁️‍🗨️ | Виɜуᴀᴧ | 👁️‍🗨️",
        " 🔫 | Оᴩужиᴇ  | 🔫",
        " 💫 | Тᴇᴧᴇᴨᴏᴩᴛᴀция | 💫",
        " 💼 | Бᴏᴛы дᴧя ᴩᴀбᴏᴛ | 💼", 
        " ⛔ | Выхᴏд | ⛔", 
    }, nil, centeredTitle .. "\n" .. dateTimeLine .. "\n Вᴇᴩᴄия ᴄᴋᴩиᴨᴛᴀ: 1.56" )  -- Используем центрированный заголовок, дату/время и архитектуру

    if main == 1 then persona() end
    if main == 2 then car() end
    if main == 3 then visual() end
    if main == 4 then gun() end
    if main == 5 then teleport() end
    if main == 6 then bots() end
    if main == 7 then exit() end
end
function bots() 

active = 0
main3239 = gg.choice({
         " Сᴨиᴄᴏᴋ бᴏᴛᴏʙ ",
         " Тᴇᴧᴇᴨᴏᴩᴛ на работу",

                  }, nil, '')  

if main3239 == 1 then listbot() end
if main3239 == 2 then teleportr() end
end
function teleportr() 
local main12 = gg.choice({
        "  📦 Сᴏᴩᴛиᴩᴏʙᴏчный цᴇнᴛᴩ",
        "  🧑‍🌾 Фᴇᴩʍᴀ", 
        "  🏭 Зᴀʙᴏд Тʙиᴋᴄ", 
        "  ⛏️ Кᴀʍнᴇᴧᴏʍня", 
    }, nil, " Выберите точку")
    
    if main12 == 1 then sortir() end
    if main12 == 2 then ferma() end  
    if main12 == 3 then twix() end
    if main12 == 4 then kamen() end
    end
    function kamen() 
    gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1039807637", gg.TYPE_DWORD)
local results = gg.getResults(101)
if #results == 0 then
  gg.alert("Значение не найдено")
  return
end

local baseAddress = results[1].address

local offsetX = 0x80
local offsetY = 0x84
local offsetZ = 0x88

local addrX = baseAddress + offsetX
local addrY = baseAddress + offsetY
local addrZ = baseAddress + offsetZ

local coords = gg.getValues({
  {address = addrX, flags = gg.TYPE_FLOAT},
  {address = addrY, flags = gg.TYPE_FLOAT},
  {address = addrZ, flags = gg.TYPE_FLOAT}
})

gg.toast(string.format("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧняᴇᴛᴄя..", coords[1].value, coords[2].value, coords[3].value))

-- Установка новых координат (числами, без кавычек)
gg.setValues({
  {address = addrX, value =2053 , flags = gg.TYPE_FLOAT},
  {address = addrY, value =-696 , flags = gg.TYPE_FLOAT},
  {address = addrZ, value = 12.4, flags = gg.TYPE_FLOAT}
})

gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн")
end
    function twix()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1039807637", gg.TYPE_DWORD)
local results = gg.getResults(101)
if #results == 0 then
  gg.alert("Значение не найдено")
  return
end

local baseAddress = results[1].address

local offsetX = 0x80
local offsetY = 0x84
local offsetZ = 0x88

local addrX = baseAddress + offsetX
local addrY = baseAddress + offsetY
local addrZ = baseAddress + offsetZ

local coords = gg.getValues({
  {address = addrX, flags = gg.TYPE_FLOAT},
  {address = addrY, flags = gg.TYPE_FLOAT},
  {address = addrZ, flags = gg.TYPE_FLOAT}
})

gg.toast(string.format("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧняᴇᴛᴄя..", coords[1].value, coords[2].value, coords[3].value))

-- Установка новых координат (числами, без кавычек)
gg.setValues({
  {address = addrX, value = 2263.51318359375, flags = gg.TYPE_FLOAT},
  {address = addrY, value = 2149.2109375, flags = gg.TYPE_FLOAT},
  {address = addrZ, value = 17 , flags = gg.TYPE_FLOAT}
})

gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн")
end
function sortir()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1039807637", gg.TYPE_DWORD)
local results = gg.getResults(101)
if #results == 0 then
  gg.alert("Значение не найдено")
  return
end

local baseAddress = results[1].address

local offsetX = 0x80
local offsetY = 0x84
local offsetZ = 0x88

local addrX = baseAddress + offsetX
local addrY = baseAddress + offsetY
local addrZ = baseAddress + offsetZ

local coords = gg.getValues({
  {address = addrX, flags = gg.TYPE_FLOAT},
  {address = addrY, flags = gg.TYPE_FLOAT},
  {address = addrZ, flags = gg.TYPE_FLOAT}
})

gg.toast(string.format("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧняᴇᴛᴄя..", coords[1].value, coords[2].value, coords[3].value))

-- Установка новых координат (числами, без кавычек)
gg.setValues({
  {address = addrX, value =806.8454589843 , flags = gg.TYPE_FLOAT},
  {address = addrY, value =1353.84033203125 , flags = gg.TYPE_FLOAT},
  {address = addrZ, value = 15 , flags = gg.TYPE_FLOAT}
})

gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн")
end
function ferma()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1039807637", gg.TYPE_DWORD)
local results = gg.getResults(101)
if #results == 0 then
  gg.alert("Значение не найдено")
  return
end

local baseAddress = results[1].address

local offsetX = 0x80
local offsetY = 0x84
local offsetZ = 0x88

local addrX = baseAddress + offsetX
local addrY = baseAddress + offsetY
local addrZ = baseAddress + offsetZ

local coords = gg.getValues({
  {address = addrX, flags = gg.TYPE_FLOAT},
  {address = addrY, flags = gg.TYPE_FLOAT},
  {address = addrZ, flags = gg.TYPE_FLOAT}
})

gg.toast(string.format("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧняᴇᴛᴄя..", coords[1].value, coords[2].value, coords[3].value))

-- Установка новых координат (числами, без кавычек)
gg.setValues({
  {address = addrX, value = 949.01531982422 , flags = gg.TYPE_FLOAT},
  {address = addrY, value = -916.6235351562, flags = gg.TYPE_FLOAT},
  {address = addrZ, value = 40 , flags = gg.TYPE_FLOAT}
})

gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн")
end
function listbot()
gg.alert("❗Дᴧя дᴀннᴏй ɸунᴋции нᴇᴏбхᴏдиʍ ᴀʙᴛᴏᴋᴧиᴋᴇᴩ ❗")
gg.sleep("200") 
active = 0
main32300 = gg.choice({
         " 🧑‍🌾 | Бᴏᴛ нᴀ ɸᴇᴩʍу | 🧑‍🌾 ",
         " 🏭 | Бᴏᴛ нᴀ ɜᴀʙᴏд Тʙиᴋᴄ |  🏭 ", 
         " 📦 | Бᴏᴛ нᴀ ᴄᴏᴩᴛиᴩᴏʙᴏчный цᴇнᴛᴩ | 📦", 
         " ⛏️ | Бᴏᴛ нᴀ ᴋᴀʍнᴇᴧᴏʍню | ⛏️", 

                  }, nil, '')  
          if main32300 == 1 then fermabot() end
          if main32300 == 2 then twixbot() end
          if main32300 == 3 then sortirbot() end
          if main32300 == 4 then kamenbot() end
end
function kamenbot() 
gg.setVisible(false)
mark_coords = nil
pers_coords = nil
baseTeleportAddress = nil

local continueLoop = true -- Переменная для управления циклом
function ainCycle()
    -- Проверка, открыто ли меню GG
    if gg.isVisible() then
        -- Спрашиваем у пользователя, хочет ли он прервать цикл
        local answer = gg.choice({"Прервать фарм", "Продолжить"}, 1)
        if answer == 1 then
            gg.toast("Фарм остановлен пользователем.")
            return -- Выход из рекурсии, завершение цикла
        else
--Скрываем меню GG и продолжаем цикл
        end
    end

    -- Весь ваш код здесь (тот что вы прислали)

    gg.clearResults()
    gg.setVisible(false)

    -- Поиск метки только если координаты ещё не найдены
    if not mark_coords then
        gg.setRanges(gg.REGION_C_BSS)
        gg.searchNumber("1176256512", gg.TYPE_DWORD)
        local mark = gg.getResults(101)
        if #mark == 0 then
            gg.alert("Чекпоинт не найден!")
            return -- Можно завершить или продолжить по желанию
        end

        mark_base = mark[1].address
        mark_coords = {
            {address = mark_base + 0x21EC, flags = gg.TYPE_FLOAT}, -- X
            {address = mark_base + 0x21F0, flags = gg.TYPE_FLOAT}, -- Y
            {address = mark_base + 0x21F4, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Обновляем значения координат метки перед телепортом
    local current_mark = gg.getValues(mark_coords)

    -- Проверка на 0 0 0
    if current_mark[1].value == 0 and current_mark[2].value == 0 and current_mark[3].value == 0 then
        gg.alert("Вам нужно поступить на работу для бота !")
        return
    end

    -- Поиск координат персонажа, если ещё не найдено
    if not pers_coords then
        gg.clearResults()
        gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local pers = gg.getResults(111)
        if #pers == 0 then
            gg.alert("Координаты персонажа не найдены!")
            return
        end

        local pers_base = pers[1].address
        pers_coords = {
            {address = pers_base + 0x80, flags = gg.TYPE_FLOAT}, -- X
            {address = pers_base + 0x84, flags = gg.TYPE_FLOAT}, -- Y
            {address = pers_base + 0x88, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Телепорт персонажа с обновленными значениями координат метки
    local success = gg.setValues({
        {address=pers_coords[1].address, value=current_mark[1].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[2].address, value=current_mark[2].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[3].address, value=current_mark[3].value, flags=gg.TYPE_FLOAT}
    })

    if success then
        gg.toast("Телепортация выполнена")
    else
        gg.alert("Ошибка при телепортации!")
    end

    function setCoords(x,y,z)
      if baseTeleportAddress == nil then 
          gg.clearResults()
          gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
          gg.searchNumber("1039807637",gg.TYPE_DWORD)
          local r=gg.getResults(100)

          if #r==0 then 
              gg.alert("Не удалось найти адрес телепорта")
              return 
          end 

          baseTeleportAddress=r[1].address 
          gg.toast("Адрес телепорта найден и сохранён!") 
      else 
          gg.toast("Используем сохранённый адрес телепорта.")
      end 

      local values={
          {address=baseTeleportAddress+0x80,flags=gg.TYPE_FLOAT,value=x},
          {address=baseTeleportAddress+0x84,flags=gg.TYPE_FLOAT,value=y},
          {address=baseTeleportAddress+0x88,flags=gg.TYPE_FLOAT,value=z}
      }

      local successSetValues=gg.setValues(values)

      if successSetValues then 
          gg.toast("Координаты установлены")
      else 
          print("Ошибка установки координат")
      end 
   end

   -- Задержка перед следующим вызовом функции (например 5 секунд)
   gg.sleep(5000)

   -- Рекурсивный вызов для следующего цикла без использования while/try/do-while.
   ainCycle()
end

-- Запуск первого вызова функции для начала цикла.
ainCycle()

-- После завершения цикла можно вывести сообщение или выполнить финальные действия.
gg.toast("Бот завершен.")
end
function fermabot() 
gg.setVisible(false)
mark_coords = nil
pers_coords = nil
baseTeleportAddress = nil

local continueLoop = true -- Переменная для управления циклом
function mainCycle()
    -- Проверка, открыто ли меню GG
    if gg.isVisible() then
        -- Спрашиваем у пользователя, хочет ли он прервать цикл
        local answer = gg.choice({"Прервать фарм", "Продолжить"}, 1)
        if answer == 1 then
            gg.toast("Фарм остановлен пользователем.")
            return -- Выход из рекурсии, завершение цикла
        else
--Скрываем меню GG и продолжаем цикл
        end
    end

    -- Весь ваш код здесь (тот что вы прислали)

    gg.clearResults()
    gg.setVisible(false)

    -- Поиск метки только если координаты ещё не найдены
    if not mark_coords then
        gg.setRanges(gg.REGION_C_BSS)
        gg.searchNumber("1176256512", gg.TYPE_DWORD)
        local mark = gg.getResults(101)
        if #mark == 0 then
            gg.alert("Чекпоинт не найден!")
            return -- Можно завершить или продолжить по желанию
        end

        mark_base = mark[1].address
        mark_coords = {
            {address = mark_base + 0x21D0, flags = gg.TYPE_FLOAT}, -- X
            {address = mark_base + 0x21D4, flags = gg.TYPE_FLOAT}, -- Y
            {address = mark_base + 0x21D8, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Обновляем значения координат метки перед телепортом
    local current_mark = gg.getValues(mark_coords)

    -- Проверка на 0 0 0
    if current_mark[1].value == 0 and current_mark[2].value == 0 and current_mark[3].value == 0 then
        gg.alert("Вам нужно поступить на работу для бота !")
        return
    end

    -- Поиск координат персонажа, если ещё не найдено
    if not pers_coords then
        gg.clearResults()
        gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local pers = gg.getResults(111)
        if #pers == 0 then
            gg.alert("Координаты персонажа не найдены!")
            return
        end

        local pers_base = pers[1].address
        pers_coords = {
            {address = pers_base + 0x80, flags = gg.TYPE_FLOAT}, -- X
            {address = pers_base + 0x84, flags = gg.TYPE_FLOAT}, -- Y
            {address = pers_base + 0x88, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Телепорт персонажа с обновленными значениями координат метки
    local success = gg.setValues({
        {address=pers_coords[1].address, value=current_mark[1].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[2].address, value=current_mark[2].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[3].address, value=current_mark[3].value, flags=gg.TYPE_FLOAT}
    })

    if success then
        gg.toast("Телепортация выполнена")
    else
        gg.alert("Ошибка при телепортации!")
    end

    function setCoords(x,y,z)
      if baseTeleportAddress == nil then 
          gg.clearResults()
          gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
          gg.searchNumber("1039807637",gg.TYPE_DWORD)
          local r=gg.getResults(100)

          if #r==0 then 
              gg.alert("Не удалось найти адрес телепорта")
              return 
          end 

          baseTeleportAddress=r[1].address 
          gg.toast("Адрес телепорта найден и сохранён!") 
      else 
          gg.toast("Используем сохранённый адрес телепорта.")
      end 

      local values={
          {address=baseTeleportAddress+0x80,flags=gg.TYPE_FLOAT,value=x},
          {address=baseTeleportAddress+0x84,flags=gg.TYPE_FLOAT,value=y},
          {address=baseTeleportAddress+0x88,flags=gg.TYPE_FLOAT,value=z}
      }

      local successSetValues=gg.setValues(values)

      if successSetValues then 
          gg.toast("Координаты установлены")
      else 
          print("Ошибка установки координат")
      end 
   end

   -- Задержка перед следующим вызовом функции (например 5 секунд)
   gg.sleep(1800)

   -- Рекурсивный вызов для следующего цикла без использования while/try/do-while.
   mainCycle()
end

-- Запуск первого вызова функции для начала цикла.
mainCycle()

-- После завершения цикла можно вывести сообщение или выполнить финальные действия.
gg.toast("Бот завершен.")
end
function twixbot() 
gg.setVisible(false)
mark_coords = nil
pers_coords = nil
baseTeleportAddress = nil

local continueLoop = true -- Переменная для управления циклом
function mainCyc()
    -- Проверка, открыто ли меню GG
    if gg.isVisible() then
        -- Спрашиваем у пользователя, хочет ли он прервать цикл
        local answer = gg.choice({"Прервать фарм", "Продолжить"}, 1)
        if answer == 1 then
            gg.toast("Фарм остановлен пользователем.")
            return -- Выход из рекурсии, завершение цикла
        else
--Скрываем меню GG и продолжаем цикл
        end
    end

    -- Весь ваш код здесь (тот что вы прислали)

    gg.clearResults()
    gg.setVisible(false)

    -- Поиск метки только если координаты ещё не найдены
    if not mark_coords then
        gg.setRanges(gg.REGION_C_BSS)
        gg.searchNumber("1176256512", gg.TYPE_DWORD)
        local mark = gg.getResults(101)
        if #mark == 0 then
            gg.alert("Чекпоинт не найден!")
            return -- Можно завершить или продолжить по желанию
        end

        mark_base = mark[1].address
        mark_coords = {
            {address = mark_base + 0x21D0, flags = gg.TYPE_FLOAT}, -- X
            {address = mark_base + 0x21D4, flags = gg.TYPE_FLOAT}, -- Y
            {address = mark_base + 0x21D8, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Обновляем значения координат метки перед телепортом
    local current_mark = gg.getValues(mark_coords)

    -- Проверка на 0 0 0
    if current_mark[1].value == 0 and current_mark[2].value == 0 and current_mark[3].value == 0 then
        gg.alert("Вам нужно поступить на работу для бота !")
        return
    end

    -- Поиск координат персонажа, если ещё не найдено
    if not pers_coords then
        gg.clearResults()
        gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local pers = gg.getResults(111)
        if #pers == 0 then
            gg.alert("Координаты персонажа не найдены!")
            return
        end

        local pers_base = pers[1].address
        pers_coords = {
            {address = pers_base + 0x80, flags = gg.TYPE_FLOAT}, -- X
            {address = pers_base + 0x84, flags = gg.TYPE_FLOAT}, -- Y
            {address = pers_base + 0x88, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Телепорт персонажа с обновленными значениями координат метки
    local success = gg.setValues({
        {address=pers_coords[1].address, value=current_mark[1].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[2].address, value=current_mark[2].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[3].address, value=current_mark[3].value, flags=gg.TYPE_FLOAT}
    })

    if success then
        gg.toast("Телепортация выполнена")
    else
        gg.alert("Ошибка при телепортации!")
    end

    function setCoords(x,y,z)
      if baseTeleportAddress == nil then 
          gg.clearResults()
          gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
          gg.searchNumber("1039807637",gg.TYPE_DWORD)
          local r=gg.getResults(100)

          if #r==0 then 
              gg.alert("Не удалось найти адрес телепорта")
              return 
          end 

          baseTeleportAddress=r[1].address 
          gg.toast("Адрес телепорта найден и сохранён!") 
      else 
          gg.toast("Используем сохранённый адрес телепорта.")
      end 

      local values={
          {address=baseTeleportAddress+0x80,flags=gg.TYPE_FLOAT,value=x},
          {address=baseTeleportAddress+0x84,flags=gg.TYPE_FLOAT,value=y},
          {address=baseTeleportAddress+0x88,flags=gg.TYPE_FLOAT,value=z}
      }

      local successSetValues=gg.setValues(values)

      if successSetValues then 
          gg.toast("Координаты установлены")
      else 
          print("Ошибка установки координат")
      end 
   end

   -- Задержка перед следующим вызовом функции (например 5 секунд)
   gg.sleep(3000)

   -- Рекурсивный вызов для следующего цикла без использования while/try/do-while.
   mainCyc()
end

-- Запуск первого вызова функции для начала цикла.
mainCyc()

-- После завершения цикла можно вывести сообщение или выполнить финальные действия.
gg.toast("Бот завершен.")
end
function sortirbot() 
gg.setVisible(false)
mark_coords = nil
pers_coords = nil
baseTeleportAddress = nil

local continueLoop = true -- Переменная для управления циклом
function mainCycl()
    -- Проверка, открыто ли меню GG
    if gg.isVisible() then
        -- Спрашиваем у пользователя, хочет ли он прервать цикл
        local answer = gg.choice({"Прервать фарм", "Продолжить"}, 1)
        if answer == 1 then
            gg.toast("Фарм остановлен пользователем.")
            return -- Выход из рекурсии, завершение цикла
        else
--Скрываем меню GG и продолжаем цикл
        end
    end

    -- Весь ваш код здесь (тот что вы прислали)

    gg.clearResults()
    gg.setVisible(false)

    -- Поиск метки только если координаты ещё не найдены
    if not mark_coords then
        gg.setRanges(gg.REGION_C_BSS)
        gg.searchNumber("1176256512", gg.TYPE_DWORD)
        local mark = gg.getResults(101)
        if #mark == 0 then
            gg.alert("Чекпоинт не найден!")
            return -- Можно завершить или продолжить по желанию
        end

        mark_base = mark[1].address
        mark_coords = {
            {address = mark_base + 0x21D0, flags = gg.TYPE_FLOAT}, -- X
            {address = mark_base + 0x21D4, flags = gg.TYPE_FLOAT}, -- Y
            {address = mark_base + 0x21D8, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Обновляем значения координат метки перед телепортом
    local current_mark = gg.getValues(mark_coords)

    -- Проверка на 0 0 0
    if current_mark[1].value == 0 and current_mark[2].value == 0 and current_mark[3].value == 0 then
        gg.alert("Вам нужно поступить на работу для бота !")
        return
    end

    -- Поиск координат персонажа, если ещё не найдено
    if not pers_coords then
        gg.clearResults()
        gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local pers = gg.getResults(111)
        if #pers == 0 then
            gg.alert("Координаты персонажа не найдены!")
            return
        end

        local pers_base = pers[1].address
        pers_coords = {
            {address = pers_base + 0x80, flags = gg.TYPE_FLOAT}, -- X
            {address = pers_base + 0x84, flags = gg.TYPE_FLOAT}, -- Y
            {address = pers_base + 0x88, flags = gg.TYPE_FLOAT}  -- Z
        }
    end

    -- Телепорт персонажа с обновленными значениями координат метки
    local success = gg.setValues({
        {address=pers_coords[1].address, value=current_mark[1].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[2].address, value=current_mark[2].value, flags=gg.TYPE_FLOAT},
        {address=pers_coords[3].address, value=current_mark[3].value, flags=gg.TYPE_FLOAT}
    })

    if success then
        gg.toast("Телепортация выполнена")
    else
        gg.alert("Ошибка при телепортации!")
    end

    function setCoords(x,y,z)
      if baseTeleportAddress == nil then 
          gg.clearResults()
          gg.setRanges( bit32.bor(gg.REGION_C_ALLOC,gg.REGION_OTHER) )
          gg.searchNumber("1039807637",gg.TYPE_DWORD)
          local r=gg.getResults(100)

          if #r==0 then 
              gg.alert("Не удалось найти адрес телепорта")
              return 
          end 

          baseTeleportAddress=r[1].address 
          gg.toast("Адрес телепорта найден и сохранён!") 
      else 
          gg.toast("Используем сохранённый адрес телепорта.")
      end 

      local values={
          {address=baseTeleportAddress+0x80,flags=gg.TYPE_FLOAT,value=x},
          {address=baseTeleportAddress+0x84,flags=gg.TYPE_FLOAT,value=y},
          {address=baseTeleportAddress+0x88,flags=gg.TYPE_FLOAT,value=z}
      }

      local successSetValues=gg.setValues(values)

      if successSetValues then 
          gg.toast("Координаты установлены")
      else 
          print("Ошибка установки координат")
      end 
   end

   -- Задержка перед следующим вызовом функции (например 5 секунд)
   gg.sleep(1800)

   -- Рекурсивный вызов для следующего цикла без использования while/try/do-while.
   mainCycl() 
  
end

-- Запуск первого вызова функции для начала цикла.
mainCycl() 
end 
function teleport()
active = 0
main323 = gg.choice({

         " Тᴇᴧᴇᴨᴏᴩᴛ ᴨᴏ ʍᴇᴛᴋᴇ ",
         " Тᴇᴧᴇᴨᴏᴩᴛ ᴨᴏ ᴋᴏᴏᴩдинᴀᴛᴀʍ ",

                  }, nil, '')  
          if main323 == 1 then metka() end
          if main323 == 2 then coordinats() end
          end
          function metka()
          active = 0
main3232 = gg.choice({
         " Тᴇᴧᴇᴨᴏᴩᴛиᴩᴏвᴀᴛься",
         " Вᴇᴩнуᴛьᴄя нᴀ Зᴇʍᴧю(ᴇᴄᴧи ʙы ᴨᴏд ᴋᴀᴩᴛᴏй)  ",

                  }, nil, '')  
          if main3232 == 1 then metkatp() end
          if main3232 == 2 then backnapol() end
          end
          function backnapol() 
          modifyCharacterPosition(110.0)
    
         end
          function metkatp()
          
-- Глобальные переменные для хранения координат
-- Глобальные переменные для хранения координат
mark_coords = nil
pers_coords = nil
baseTeleportAddress = nil

    gg.clearResults()
    gg.setVisible(false)

    -- Поиск метки только если координаты ещё не найдены
    if not mark_coords then
        gg.setRanges(gg.REGION_C_BSS)
        gg.searchNumber("1180457", gg.TYPE_DWORD)
        local mark = gg.getResults(1)
        if #mark == 0 then
            gg.alert("Метка не найдена!")
            return
        end

        mark_base = mark[1].address
        mark_coords = {
            {address = mark_base - 0x20, flags = gg.TYPE_FLOAT}, -- X
            {address = mark_base - 0x1C, flags = gg.TYPE_FLOAT}-- Y
        }
    end

    -- Обновляем значения координат метки перед телепортом
    local current_mark = gg.getValues(mark_coords)

    -- Проверка на 0 0 0
    if current_mark[1].value == 0 and current_mark[2].value == 0 and current_mark[3].value == 0 then
        gg.alert("Вам нужно поставить метку для телепортации!")
        return
    end

    -- Поиск координат персонажа, если ещё не найдено
    if not pers_coords then
        gg.clearResults()
        gg.setRanges(gg.REGION_C_ALLOC)
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local pers = gg.getResults(1)
        if #pers == 0 then
            gg.alert("Координаты персонажа не найдены!")
            return
        end

        local pers_base = pers[1].address
        pers_coords = {
            {address = pers_base + 0x80, flags = gg.TYPE_FLOAT}, -- X
            {address = pers_base + 0x84, flags = gg.TYPE_FLOAT} -- Y
        }
    end

    -- Телепорт персонажа с обновленными значениями координат метки
    local success = gg.setValues({
        {address = pers_coords[1].address, value = current_mark[1].value, flags = gg.TYPE_FLOAT},
        {address = pers_coords[2].address, value = current_mark[2].value, flags = gg.TYPE_FLOAT}
    })

    if success then
        gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн!")
    else
        gg.alert("Ошибка при телепортации!")
    end

function setCoords(x, y, z)
    if baseTeleportAddress == nil then
        gg.clearResults()
        gg.setRanges(gg.REGION_C_ALLOC)
        gg.searchNumber("1039807637", gg.TYPE_DWORD)
        local r = gg.getResults(100)

        if #r == 0 then
            gg.alert("Координаты не найдены! ⚠️")
            return
        end

        baseTeleportAddress = r[1].address
        gg.toast("Адрес телепорта найден и сохранён!")
    else 
        gg.toast("Используем сохранённый адрес телепорта.")
    end

    -- Применяем смещение ко всем координатам с новыми значениями x,y,z.
    local values = {
      {address=baseTeleportAddress + 0x80, flags=gg.TYPE_FLOAT,value=x},
      {address=baseTeleportAddress + 0x84, flags=gg.TYPE_FLOAT,value=y}
   }

   local successSetValues=gg.setValues(values)

   if successSetValues then 
       gg.toast("Тᴇᴧᴇᴨᴏᴩᴛ ʙыᴨᴏᴧнᴇн! ✨")
   else 
       print("Ошибка при установке значений.")
   end 
end

          end
          function coordinats()
          -- Устанавливаем диапазон поиска
    local target_value = 1039807637  -- Замените на нужное значение

    -- Функция для поиска значения
    function find_value(value)
        gg.setRanges(gg.REGION_C_ALLOC)  -- Устанавливаем диапазон поиска
        gg.searchNumber(value, gg.TYPE_DWORD)  -- Ищем значение как DWORD
        return gg.getResults(gg.getResultsCount())  -- Получаем результаты поиска
    end

    -- Функция для изменения значений по смещениям
    function modify_values(found_results)
    -- Смещения для координат (в байтах), используем отрицательные значения для смещения вверх
    local offsets = {
        x = 0x80,
        y = 0x84,
        z = 0x88
    }

    for i, result in ipairs(found_results) do
        local base_address = result.address
        
        -- Изменение координаты X
        local new_x_value = gg.prompt({"Введите новое значение для X:"}, {0})
        if new_x_value and new_x_value[1] then  -- Проверяем на nil и наличие первого элемента
            local x_address = base_address + offsets.x
            gg.setValues({{address=x_address, flags=gg.TYPE_FLOAT, value=new_x_value[1]}})
            gg.alert("Значение X изменено" )
        end
        
        -- Изменение координаты Y
        local new_y_value = gg.prompt({"Введите новое значение для Y:"}, {0})
        if new_y_value and new_y_value[1] then  -- Проверяем на nil и наличие первого элемента
            local y_address = base_address + offsets.y
            gg.setValues({{address=y_address, flags=gg.TYPE_FLOAT, value=new_y_value[1]}})
            gg.alert("Значение Y изменено" )
        end
        
        -- Изменение координаты Z
        local new_z_value = gg.prompt({"Введите новое значение для Z:"}, {0})
        if new_z_value and new_z_value[1] then  -- Проверяем на nil и наличие первого элемента
            local z_address = base_address + offsets.z
            gg.setValues({{address=z_address, flags=gg.TYPE_FLOAT, value=new_z_value[1]}})
            gg.alert("Значение Z изменено" )
        end
        
        break  -- Удалите эту строку, если хотите изменить все найденные адреса.
    end
end

    -- Основная логика скрипта
    local found_results = find_value(target_value)

    if #found_results > 0 then
        gg.alert("Координаты найдены! ")
        modify_values(found_results)  -- Вызываем функцию изменения значений
    else
        gg.toast("Значение не найдено.")
    end

     
     end
          function mesta()
gg.alert("В разработке")
end
-- Запуск меню
function persona()
gg.clearResults() 
active = 0
main1 = gg.choice({
         "💯 | Бᴇᴄᴄʍᴇᴩᴛиᴇ | 💯", 
         "⚰️ | Суицид | ⚰️", 
         "🛡 | Выдᴀчᴀ бᴩᴏни | 🛡", 
         "🏃‍♂️ | Быᴄᴛᴩый бᴇᴦ | 🏃‍♂️",
         "↩️ | Рᴇɜᴋиᴇ ᴨᴏʙᴏᴩᴏᴛы | ↩️",
         "🦸‍♂️ | Выᴄᴏᴋий ᴨᴩыжᴏᴋ | 🦸‍♂️", 
         "🦸‍♀️ | Дᴧинный ᴨᴩыжᴏᴋ | 🦸‍♀️", 
         "🔛 | Сʍᴇщᴇниᴇ ᴨᴏ ᴏᴄяʍ X/Y | 🔛",
         "⬆️ | Пᴏдбᴩᴏᴄиᴛь ʙʙᴇᴩх | ⬆️",
         "⬇️ | Пᴏдбᴩᴏᴄиᴛь ʙниɜ | ⬇️", 
         }, nil, '') 
         if main1 == 1 then immortality() end
         if main1 == 2 then suicide() end
         if main1 == 3 then armour() end
         if main1 == 4 then fastbeg() end
         if main1 == 5 then stamina() end
         if main1 == 6 then povor() end
         if main1 == 7 then bigjump() end
         if main1 == 8 then longjump() end
         if main1 == 9 then xy() end
         if main1 == 10 then slapup() end
         if main1 == 11 then slapdown() end
         end
         function immortality() 
         active = 0
main3 = gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main3 == 1 then on() end
          if main3 == 2 then off() end
          end
          function on() 
         local searchValue = 100.14399719238 -- Значение для поиска бессмертия.
    local offset = 4 -- Смещение.
    local freezeValue = 5000 -- Значение для заморозки.

    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_FLOAT)

    local results = gg.getResults(gg.getResultsCount())

    if #results == 0 then
        gg.toast("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address - offset
        
        gg.setValues({
            {
                address = address,
                flags=gg.TYPE_FLOAT,
                value=freezeValue,
            }
         })

         gg.addListItems({
             {
                 address=address,
                 flags=gg.TYPE_FLOAT,
                 value=freezeValue,
                 freeze=true -- Устанавливаем флаг заморозки.
             }
         })
     end

     gg.toast("Бессмертие включено")
end
function off() 
local searchValue = 100.14399719238 -- Значение для поиска бессмертия.
local offset = 4 -- Смещение.
local newValue = 100 -- Новое значение для замены.

gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(searchValue, gg.TYPE_FLOAT)

local results = gg.getResults(gg.getResultsCount())

if #results == 0 then
    gg.toast("Значение не найдено.")
    return
end

for i = 1, #results do
    local address = results[i].address - offset
    
    -- Удаляем заморозку с адреса
    gg.removeListItems({
        {
            address=address,
            flags=gg.TYPE_FLOAT,
        }
    })

    -- Устанавливаем новое значение
    gg.setValues({
        {
            address=address,
            flags=gg.TYPE_FLOAT,
            value=newValue,
        }
    })
end

gg.toast("Бессмертие отключено ") 
end
function suicide() 
    gg.clearResults()
    local searchValue = 100.14399719238 -- Значение для поиска.
    local offset = 4 

    function changeValue()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue, gg.TYPE_FLOAT)

       local results=gg.getResults(gg.getResultsCount())

       if #results == 0 then return end 

       for i=1,#results do 
           local address=results[i].address-offset 

           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=0.0,
               }
           })
       end 

       gg.toast("Суицид был активирован")
   end 

   changeValue()
end 
function armour() 
 gg.clearResults()
   local searchValue=100.14399719238     
   local offset=4 

   function changeValue()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue,gg.TYPE_FLOAT)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=100,
               }
           })
       end 

       gg.toast("Успешно выдана броня")
   end
   
   changeValue()
end 
function fastbeg()
active = 0
main4 = gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main4 == 1 then one() end
          if main4 == 2 then offe() end
          end
          function one() 
            local searchValue = 409099829248
    local offset = 0x20
    local freezeValue = -0.5

    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(1000)

    if #results == 0 then
        gg.toast("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = freezeValue,
            }
        })

        gg.addListItems({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = freezeValue,
                freeze=true -- Устанавливаем флаг заморозки для быстрого бега.
            }
        })
    end

    gg.toast("Быстрый бег включен")
end
function offe() 
  local searchValue = 409099829248
    local offset = 0x20
    local freezeValue = 0.69

    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(1000)

    if #results == 0 then
        gg.toast("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = freezeValue,
            }
        })

        gg.addListItems({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = freezeValue,
                freeze=true -- Устанавливаем флаг заморозки для быстрого бега.
            }
        })
    end

    gg.toast("Быстрый бег выключен")
end
function stamina() 
-- Установите значение, которое вы хотите заморозить
local targetValue = 1150271488 -- Ваше значение стамины
local offset = -0x34 -- Смещение от найденного адреса

    gg.setRanges(gg.REGION_C_ALLOC)
-- Функция для поиска и заморозки значения стамины
function freezeStamina()
    -- Ищем заданное значение в памяти
    gg.searchNumber(targetValue, gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
    
    -- Получаем результаты поиска
    local results = gg.getResults(1000)
    
    -- Проверяем, найден ли адрес
    if #results > 0 then
        -- Вычисляем адрес стамины с учетом смещения
        local staminaAddress = results[1].address + offset
        
        -- Добавляем элемент в список GameGuardian для заморозки значения
        gg.addListItems({
            {
                address = staminaAddress,
                flags = gg.TYPE_FLOAT,
                value = 450.0,
                freeze = true -- Замораживаем значение
            }
        })
        
        gg.toast("Бесконечный бег включён ") -- Уведомление об успешной заморозке
    else
        gg.toast("Адрес не найден!") -- Уведомление о том, что адрес не найден
    end
end

-- Запускаем функцию заморозки стамины
freezeStamina()
end
function bigjump() 
    active = 0
    main8 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    if main8 == 1 then oaon() end
    if main8 == 2 then oaooff() end
end
function oaon() 
    local searchValue=1.65439337e-24 -- Значение для поиска.
   local replaceValue=10.0 -- Новое значение.
   local offset=0x88 -- Смещение.

   function replaceValueInAlloc()
      -- Устанавливаем параметры поиска.
      gg.setRanges(gg.REGION_C_ALLOC)
      
      -- Ищем заданное значение в области памяти alloc.
      gg.searchNumber(searchValue,gg.TYPE_FLOAT)
      
      -- Получаем результаты поиска.
      local results=gg.getResults(gg.getResultsCount())
      
      if #results==0 then return end
      
      for i,v in ipairs(results) do 
          -- Получаем адрес найденного значения с учетом смещения.
          local address=v.address+offset
        
          -- Заменяем значение на новое.
          gg.setValues({
              {address=address,flags=gg.TYPE_FLOAT,value=replaceValue}
          })
          
          -- Уведомляем о завершении операции.
          gg.toast("Высокий прыжок включен") 
      end
      
      -- Уведомляем о завершении операции.
      gg.toast("Высокий прыжок включен.")
  end
  
  replaceValueInAlloc()  
end
function oaooff() 
    local searchValue=1.65439337e-24 -- Значение для поиска.
   local replaceValue=70.0 -- Новое значение.
   local offset=0x88 -- Смещение.

   function replaceValueInOther()
      -- Устанавливаем параметры поиска.
      gg.setRanges(gg.REGION_C_ALLOC)
      
      -- Ищем заданное значение в области памяти alloc.
      gg.searchNumber(searchValue,gg.TYPE_FLOAT)
      
      -- Получаем результаты поиска.
      local results=gg.getResults(gg.getResultsCount())
      
      if #results==0 then return end
      
      for i,v in ipairs(results) do 
          -- Получаем адрес найденного значения с учетом смещения.
          local address=v.address+offset
        
          -- Заменяем значение на новое.
          gg.setValues({
              {address=address,flags=gg.TYPE_FLOAT,value=replaceValue}
          })
          
          -- Уведомляем о завершении операции.
          gg.toast("Высокий прыжок выключен") 
      end
      
      -- Уведомляем о завершении операции.
      gg.toast("Высокий прыжок выключен.")
  end
  
  replaceValueInOther()  
end

-- Остальные функции...
    function longjump() 
    active = 0
main8 = gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main8 == 1 then ooon() end
          if main8 == 2 then oooff() end
          end
          function ooon() 
local searchValue=936480000.0-- Значение для поиска.
   local replaceValue=10-- Новое значение.
   local offset=0x18 -- Смещение.

   function replaceValueInAll()
      -- Устанавливаем параметры поиска.
      gg.setRanges(gg.REGION_CODE_APP)
      
      -- Ищем заданное значение в области памяти alloc.
      gg.searchNumber(searchValue,gg.TYPE_FLOAT)
      
      -- Получаем результаты поиска.
      local results=gg.getResults(gg.getResultsCount())
      
      if #results==0 then return end
      
      for i,v in ipairs(results) do 
          -- Получаем адрес найденного значения с учетом смещения.
          local address=v.address+offset
        
          -- Заменяем значение на новое.
          gg.setValues({
              {address=address,flags=gg.TYPE_FLOAT,value=replaceValue}
          })
          
          -- Уведомляем о завершении операции.
          gg.toast("Длинный прыжок включен") 
      end
      
      -- Уведомляем о завершении операции.
      gg.toast("Длинный прыжок включен.")
  end
  
  replaceValueInAll()  
end
    function oooff() 
        local searchValue=936480000.0-- Значение для поиска.
   local replaceValue=0.8-- Новое значение.
   local offset=0x18 -- Смещение.


   function replaceValueInAOll()
      -- Устанавливаем параметры поиска.
      gg.setRanges(gg.REGION_CODE_APP)
      
      -- Ищем заданное значение в области памяти alloc.
      gg.searchNumber(searchValue,gg.TYPE_FLOAT)
      
      -- Получаем результаты поиска.
      local results=gg.getResults(gg.getResultsCount())
      
      if #results==0 then return end
      
      for i,v in ipairs(results) do 
          -- Получаем адрес найденного значения с учетом смещения.
          local address=v.address+offset
        
          -- Заменяем значение на новое.
          gg.setValues({
              {address=address,flags=gg.TYPE_FLOAT,value=replaceValue}
          })
          
          -- Уведомляем о завершении операции.
          gg.toast("Длинный прыжок выключен") 
      end
      
      -- Уведомляем о завершении операции.
      gg.toast("Длинный прыжок выключен")
  end
  
  replaceValueInAOll()  
end
    function slapup()
   modifyCharacterPosition(10.0)
end 

function slapdown()
   modifyCharacterPosition(-10.0)
end 

function modifyCharacterPosition(addValue)
   local searchValue=-1083007583 
   local offset=0x2A4

   function changeValue()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue,gg.TYPE_DWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           local currentValue=gg.getValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
               }
           })[1].value 

           local newValue=currentValue+addValue 

           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=newValue,
               }
           })
       end 

       if addValue>0 then 
           gg.toast ("Вы были подкинуты") 
       else 
           gg.toast ("Вы были опущены") 
       end  
   end

   changeValue()
end
function car() 
gg.clearResults() 
active = 0
main10 = gg.choice({
         "🧱 | Бᴇᴄᴄʍᴇᴩᴛиᴇ ᴀʙᴛᴏʍᴏбиᴧя | 🧱", 
         "🗑 | Сᴧᴏʍᴀᴛь ʍᴀɯину | 🗑", 
         "💯 | Выдᴀᴛь ɜдᴏᴩᴏʙьᴇ ᴀʙᴛᴏʍᴏбиᴧю | 💯", 
         "⬆️ | Пᴏдᴋинуᴛь ʍᴀɯину ʙʙᴇᴩх | ⬆️", 
         "⬇️ | Пᴏдᴋинуᴛь ʍᴀɯину ʙниɜ | ⬇️",  
         "🆙 | Вɜᴧᴇᴛᴇᴛь ʙыᴄᴏᴋᴏ нᴀ 15 ᴩᴀɜ | 🆙", 
         "✈ | Пᴏᴧᴇᴛ ᴛᴩᴀнᴄᴨᴏᴩᴛᴀ | ✈",
         "🏎 | Лᴀунч - ᴋᴏнᴛᴩᴏᴧь | 🏎", 
         "🚀 | Зᴀᴨуᴄᴋ ʙ нᴇбᴏ | 🚀", 
         "🛫 | Зᴀᴨуᴄᴋ ʙ ᴋᴏᴄʍᴏᴄ | 🛫",

         }, nil, '') 
         if main10 == 1 then immortalitycar() end
         if main10 == 2 then suicidecar() end
         if main10 == 3 then hpcar() end
         if main10 == 4 then slapupcar() end
         if main10 == 5 then slapdowncar() end
         if main10 == 6 then raz() end
         if main10 == 7 then flycarr() end
         if main10 == 8 then launch() end
         if main10 == 9 then letgo() end
         if main10 == 10 then kosm() end
       
         end
         function flycarr()
         active = 0
    main122220002 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    
    if main122220002 == 1 then flycarron() end
    if main122220002 == 2 then flycarroff() end
end

function flycarron() 
    gg.clearResults()
    local searchValue = -4719772406288220160
    local offset = 0x188

    gg.setRanges(gg.REGION_C_BSS)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_DWORD,
                value = 1,
            }
        })
    end 

    gg.toast("Полет включен")
end

function flycarroff() 
    gg.clearResults()
    local searchValue = -4719772406288220160
    local offset = 0x188

    gg.setRanges(gg.REGION_C_BSS)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_DWORD,
                value = 0,
            }
        })
    end 

    gg.toast("Полет выключен ")
         
end
         function immortalitycar()
          gg.clearResults()
    local searchValue = 2379808 -- Значение, которое нужно найти
    local offset = 0xC8 -- Смещение вниз (в байтах)

    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_DWORD)
    
    local results = gg.getResults(gg.getResultsCount())
    
    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    local itemsToFreeze = {}
    
    for i = 1, #results do
        local address = results[i].address + offset
        
        table.insert(itemsToFreeze, {
            address = address,
            flags = gg.TYPE_FLOAT,
            value = 1000,
            freeze = true -- Устанавливаем флаг заморозки
        })
    end

    gg.addListItems(itemsToFreeze)
    
    gg.toast("Успешно, ваша машина неуязвима")
    gg.clearResults() 
end
function suicidecar()
    gg.clearResults()
    local searchValue = 2379808 -- Значение, которое нужно найти
    local offset = 0xC8 -- Смещение вниз (в байтах)

    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_DWORD)

    local results = gg.getResults(gg.getResultsCount())

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 0,
            }
        })
    end

    gg.toast("Успешно, ваша машина убита")
    gg.clearResults() 
end

-- Функция для добавления здоровья машине
function hpcar() 
gg.clearResults()
    
    local searchValue = 2379808 -- Значение, которое нужно найти
    local offset = 0xC8 -- Смещение вниз (в байтах)

    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_DWORD)

    local results = gg.getResults(gg.getResultsCount())

   if #results == 0 then
       gg.alert("Значение не найдено.")
       return
   end

   -- Запрашиваем у пользователя новое значение здоровья 
   local userInput = gg.prompt({"Введите новое значение (например, 30 для 30 HP):"}, {30}, {"number"})
   
   if userInput == nil then return end
   
   local newValue = tonumber(userInput[1]) * 10
   
   if newValue < 400 then 
       local warningResponse = gg.alert("Внимание! Значение меньше 40. Машина может сломаться. Вы хотите продолжить замену?", "Да", "Нет")
       
       if warningResponse == 2 then return end 
   end

   for i = 1, #results do
       local address = results[i].address + offset 
       
       gg.setValues({
           {
               address = address,
               flags = gg.TYPE_FLOAT,
               value = newValue,
           }
       })
   end

   gg.toast("Успешно") 
   gg.clearResults() 
end
function slapupcar() 
   gg.clearResults()  -- Очищаем результаты
local searchValue = 404750497 -- Значение, которое нужно найти
local offset = 0x48 -- Смещение вниз (в байтах)
local newValue = 0.5-- Значение, на которое нужно изменить

function up()
    gg.setRanges(gg.REGION_C_ALLOC) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_DWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Машина подкинута") 
end
up()
end
function slapdowncar()
   gg.clearResults()  -- Очищаем результаты
local searchValue = 404750497 -- Значение, которое нужно найти
local offset = 0x48 -- Смещение вниз (в байтах)
local newValue = -0.5 -- Значение, на которое нужно изменить

function down()
    gg.setRanges(gg.REGION_C_ALLOC) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_DWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Машина опущена")
end
down()
end
function raz() 
local searchValue = 404750497
    local offset = 0x48

    gg.clearResults()
    gg.searchNumber(searchValue, gg.TYPE_DWORD)
    local resultsCount = gg.getResultCount()

    if resultsCount == 0 then
        print("Значение не найдено.")
        return
    end

    local results = gg.getResults(resultsCount)
    local modifyList = {}

    for i, res in ipairs(results) do
        local targetAddress = res.address + offset

        table.insert(modifyList, {
            address = targetAddress,
            flags = gg.TYPE_FLOAT,
            value = 1.5
        })
    end

    gg.setValues(modifyList) 
end
function launch() 
gg.clearResults()  -- Очищаем результаты
local searchValue = 404750497 -- Значение, которое нужно найти
local offset = 0x44 -- Смещение вниз (в байтах)
local newValue = 1.0 -- Значение, на которое нужно изменить

function gau()
    gg.setRanges(gg.REGION_C_ALLOC) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_DWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Лаунч-Контроль ON")
end
gau()
end
function letgo() 
gg.clearResults()  -- Очищаем результаты
local searchValue = 404750497 -- Значение, которое нужно найти
local offset = 0x44 -- Смещение вниз (в байтах)
local newValue = 5.0 -- Значение, на которое нужно изменить

function immy()
    gg.setRanges(gg.REGION_C_ALLOC) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_DWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end
gg.toast("Взлет ON")
gg.clearResults() 
end
immy()
end
function flycar() 
    active = 0
    main16 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  

    if main16 == 1 then 
        ooooon() 
    elseif main16 == 2 then 
        oooooff() 
    end
end

function ooooon() 
    local searchValue = 404750497
    local offset = 0x48

    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_DWORD)
    local resultsCount = gg.getResultCount()

    if resultsCount == 0 then
        print("Значение не найдено.")
        return
    end

    local results = gg.getResults(resultsCount)
    local freezeList = {}

    for i, res in ipairs(results) do
        local targetAddress = res.address + offset

        -- Читаем текущее значение float по адресу
        local currentValue = gg.getValues({{address=targetAddress, flags=gg.TYPE_FLOAT}})[1].value

        table.insert(freezeList, {
            address = targetAddress,
            flags = gg.TYPE_FLOAT,
            value = currentValue,
            freeze = true
        })
    end

    -- Добавляем в список заморозки без изменения значений
    gg.addListItems(freezeList)
end
function oooooff()
    local searchValue = 404750497 -- Значение для поиска бессмертия.
    local offset = 0x48 -- Смещение.
    local newValue = 0 -- Новое значение для замены.

    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber(searchValue, gg.TYPE_DWORD)

    local results = gg.getResults(gg.getResultsCount())

    if #results == 0 then
        gg.toast("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset
        
        -- Удаляем заморозку с адреса
        gg.removeListItems({
            {
                address=address,
                flags=gg.TYPE_FLOAT,
            }
        })

        -- Устанавливаем новое значение
        gg.setValues({
            {
                address=address,
                flags=gg.TYPE_FLOAT,
                value=newValue,
            }
        })
    end

    gg.toast("Левитация отключена ") 
end
function visual() 
    active = 0
main20 = gg.choice({
         " 🔴 | RED CHAMS | 🔴",
         " 🔭 | FOV Hack | 🔭", 
         " 👻 | ESP NickName | 👻",
         " ⬜ | Пᴩᴏɜᴩᴀчныᴇ ᴄᴛᴇны | ⬜",
         " 🌧️ | Вᴋᴧючиᴛь дᴏждь | 🌧️",
         " ⚫ | Black Chams | ⚫",
         " 💥 | Вɜᴩыʙᴀᴛь ʙᴇᴄь ᴛᴩᴀнᴄᴨᴏᴩᴛ | 💥",
   --      " 💲 | Выдᴀᴛь ʙиᴩᴛы (ʙ ᴧᴀунчᴇᴩᴇ) | 💲",
    --     " ™️ | Иɜʍᴇниᴛь ниᴋнᴇйʍ (ʙ ᴧᴀунчᴇᴩᴇ) | ™️",
 --        " ℹ️ | Иɜʍᴇниᴛь ᴧᴏᴦин (ʙ ᴧᴀунчᴇᴩᴇ) | ℹ️",          
      }, nil, '')  
          if main20 == 1 then chams() end
          if main20 == 2 then fov() end
         if main20 == 3 then esp() end
         if main20 == 4 then walhack() end
           if main20 == 5 then osadki() end
           if main20 == 6 then blackchams() end
              if main20 == 7 then alah() end
           --   if main20 == 8 then money() end
        --      if main20 == 9 then nick() end
      --        if main20 == 10 then loginh() end
       --       end
    --          function nick()
     --         gg.alert("пися")
            --  end
     --         function loginh()
          --                  gg.alert("пися")
     --         end
         --     function money()
--gg.alert("gg")
end
function alah()
active = 0
    main212222000 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    
    if main212222000 == 1 then alahon() end
    if main212222000 == 2 then alahoff() end
end

function alahon() 
    gg.clearResults()
    local searchValue = 50.79999923706
    local offset = 56

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_FLOAT)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 1001,
            }
        })
    end 

    gg.toast("Взрывы включены")
end

function alahoff() 
    gg.clearResults()
    local searchValue = 50.79999923706
    local offset = 56

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_FLOAT)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 250,
            }
        })
    end 

    gg.toast("Взрывы выключены")
  
          end   
          function blackchams()
active = 0
    main21222200 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    
    if main21222200 == 1 then bllon() end
    if main21222200 == 2 then blloff() end
end

function bllon() 
    gg.clearResults()
    local searchValue = -999999.0
    local offset = 0x4

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_FLOAT)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = -555,
            }
        })
    end 

    gg.toast("Black Chams включен")
end

function blloff() 
    gg.clearResults()
    local searchValue = -999999.0
    local offset = 0x4

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_FLOAT)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 0.04,
            }
        })
    end 

    gg.toast("Black chams выключены")
   end
function osadki()
active = 0
    main21222000 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    
    if main21222000 == 1 then osdon() end
    if main21222000 == 2 then osdoff() end
end

function osdon() 
    gg.clearResults()
    local searchValue = 4515609228984729600
    local offset = 0x10

    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address - offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = -1,
            }
        })
    end 

    gg.toast("Дождь включен")
end

function osdoff() 
    gg.clearResults()
    local searchValue = 4515609228984729600
    local offset = 0x10

    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address - offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 0.004,
            }
        })
    end 

    gg.toast("Дождь выключен")
    end
      function walhack()
    active = 0
    main212220 = gg.choice({
        " ✅ | Вᴋᴧючиᴛь ",
        " ❌ | Выᴋᴧючиᴛь ", 
    }, nil, '')  
    
    if main212220 == 1 then walon() end
    if main212220 == 2 then waloff() end
end

function walon() 
    gg.clearResults()
    local searchValue = 77190601328179
    local offset = 0x14

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = -5,
            }
        })
    end 

    gg.toast("Прозрачные стены включены")
end

function waloff() 
    gg.clearResults()
    local searchValue = 77190601328179
    local offset = 0x14

    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber(searchValue, gg.TYPE_QWORD)

    local results = gg.getResults(100)

    if #results == 0 then 
        gg.toast("Значение не найдено!")
        return 
    end 

    for i = 1, #results do 
        local address = results[i].address + offset
        
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = 1,
            }
        })
    end 

    gg.toast("Прозрачные стены выключены")
end
        function chams()   
          active = 0
main21 =  gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main21 == 1 then chamson() end
          if main21 == 2 then chamsoff() end
          end
          function chamson() 
                     gg.clearResults()
   local searchValue=1132462073
   local offset=4 

   function change()
       gg.setRanges(gg.REGION_C_DATA)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address-offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=-1,
               }
           })
       end 

       gg.toast("Chams включены")
   end
   change()
end
function chamsoff() 
           gg.clearResults()
   local searchValue=1132462073
   local offset=4 

   function chang()
       gg.setRanges(gg.REGION_C_DATA)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address-offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=1,
               }
           })
       end 

       gg.toast("Chams включены")
   end
   chang()
   end
function fov() 
    active = 0
main21= gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main21 == 1 then ofovon() end
          if main21 == 2 then ooofffov() end
          end   
          function ofovon() 
          gg.clearResults()
   local searchValue=4392630932140457984
   local offset=8

   function cange()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address-offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=140, 
               }
           })
       end 

       gg.toast("Fov включен")
   end
   cange()
end
function esp()   
          active = 0
main2120 =  gg.choice({
         " ✅ | Вᴋᴧючиᴛь ",
         " ❌ | Выᴋᴧючиᴛь ", 
                  }, nil, '')  
          if main2120 == 1 then espon() end
          if main2120 == 2 then espoff() end
          end
          function espon() 
                     gg.clearResults()       
   local searchValue=1176256512
   local offset=8 

   function cnge()
       gg.setRanges(gg.REGION_C_BSS)
       gg.searchNumber(searchValue,gg.TYPE_DWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=9999991,
               }
           })
       end 

       gg.toast("esp включены")
   end
   cnge()
end
function espoff()        
   gg.setRanges(gg.REGION_C_BSS) -- Установить диапазон поиска
gg.searchNumber("9999991", gg.TYPE_FLOAT) -- Поиск значения 9999991
local results = gg.getResults(100) -- Получить результаты поиска
for i = 1, #results do
    results[i].value = 20 -- Изменить найденные значения на 20
end
gg.setValues(results) -- Применить изменения
gg.toast("esp выключены") -- Показать уведомление
   end
function ooofffov() 
gg.clearResults()
   local searchValue=4392630932140457984
   local offset=8

   function hange()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address-offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=70,
               }
           })
       end 

       gg.toast("FOV выключен")
   end
   hange()
end
function gun() 
gg.clearResults() 
active = 0
main80 = gg.choice({
       "🔫 | Выдᴀчᴀ ᴏᴩужия | 🔫", 
       "⬅️ | Сʍᴇщᴇниᴇ ᴨᴩицᴇᴧᴀ | ➡️", 
       "🏁 | Бᴇᴄᴋᴏнᴇчныᴇ ᴨᴀᴛᴩᴏны | 🏁", 
       "🌀 | АнᴛиПᴇᴩᴇɜᴀᴩядᴋᴀ | 🌀", 
       "🔱 | Анᴛи - Оᴛдᴀчᴀ | 🔱",  
       "🧲 | AimBot | 🧲", 
       "⚔️ | Быᴄᴛᴩᴀя ᴄᴛᴩᴇᴧьбᴀ/хᴏдьбᴀ | ⚔️",
       }, nil, '')
       if main80 == 1 then getgun() end
       if main80 == 2 then offpr() end
       if main80 == 3 then unpt() end
       if main80 == 4 then antiperez() end
       if main80 == 5 then norecoli() end
       if main80 == 6 then infiniteLoop() end
        if main80 == 7 then fastst() end
 end
 function fastst()
 active = 0
main88808 = gg.choice({     
         " ✅ Вᴋᴧючиᴛь  ", 
         " ❌ Выᴋᴧючиᴛь", 
                  }, nil, '')  
          if main88808 == 1 then faston() end
          if main88808 == 2 then fastoff() end
          end
          function faston() 
   gg.clearResults()  -- Очищаем результаты
local searchValue = 4575657222535905280 -- Значение, которое нужно найти
local offset = 0x10 -- Смещение вниз (в байтах)
local newValue = 10 -- Значение, на которое нужно изменить

function fastone()
    gg.setRanges(gg.REGION_CODE_APP) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_QWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Включено") 
end
fastone()
end
function fastoff()
gg.clearResults()  -- Очищаем результаты
local searchValue = 4575657222535905280 -- Значение, которое нужно найти
local offset = 0x10 -- Смещение вниз (в байтах)
local newValue = 1 -- Значение, на которое нужно изменить

function fastoffe()
    gg.setRanges(gg.REGION_CODE_APP) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_QWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Выключено") 
end
fastoffe()
end 
 function norecoli()
 active = 0
main8880 = gg.choice({
      
         " ✅ Вᴋᴧючиᴛь  ", 
         " ❌ Выᴋᴧючиᴛь", 
                  }, nil, '')  
          if main8880 == 1 then rexolion() end
          if main8880 == 2 then offricol() end
          end
          function rexolion() 
 gg.clearResults()
   local searchValue=3337261105772449345 
   local offset=0x28

   function recolion()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=95,
               }
           })
       end 

       gg.toast("АнтиОтдача включена ")
   end
   
   recolion()
   end
   function offricol() 
   gg.clearResults()
   local searchValue=3337261105772449345 
   local offset=0x28

   function recolioff()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=100.0 ,
               }
           })
       end 

       gg.toast("АнтиОтдача выключена ")
   end
   
   recolioff()
  
 end
 function getgun() 
 gg.alert("Возможен вылет из за выдачи оружия") 
    -- Запрашиваем у пользователя новое значение для смещения 0xC0
    -- Запрашиваем у пользователя новое значение для смещения 0xC0
    local userInputC0 = gg.prompt({"Введите новое значение для ID оружия (1-46) :"}, {nil}, {"number"})

    if userInputC0 == nil then
        gg.toast("Операция отменена")
        return
    end

    local newValueC0 = userInputC0[1]

    -- Запрашиваем у пользователя новое значение для смещения 0xCC
    local userInputCC = gg.prompt({"Введите новое значение смещения патронов (0-30000) :"}, {nil}, {"number"})

    if userInputCC == nil then
        gg.toast("Операция отменена")
        return
    end

    local newValueCC = userInputCC[1]

    -- Устанавливаем диапазон поиска
    gg.setRanges(gg.REGION_C_ALLOC)

    -- Ищем значение 100.14399719238
    gg.searchNumber("100.14399719238", gg.TYPE_FLOAT)

    -- Получаем результаты поиска
    local results = gg.getResults(100)

    if #results == 0 then
        gg.toast("Значение не найдено")
        return
    end

    -- Изменяем найденное значение и значения по смещениям 0xC0 и 0xCC
    for i, v in ipairs(results) do
        v.value = 100.14399719238  -- Меняем основное значение на то же самое (можно изменить при необходимости)
        gg.setValues({v})           -- Применяем изменения

        -- Меняем значение по смещению 0xC0
        local addressC0 = v.address + 0xC0
        gg.setValues({
            {address = addressC0, value = newValueC0, flags = gg.TYPE_DWORD}  -- Устанавливаем новое значение как dword
        })

        -- Меняем значение по смещению 0xCC
        local addressCC = v.address + 0xCC
        gg.setValues({
            {address = addressCC, value = newValueCC, flags = gg.TYPE_DWORD}  -- Устанавливаем новое значение как dword
        })
    end

    gg.toast("Значения успешно изменены")
end
 function unpt() 
gg.clearResults() -- Очищаем результаты
local searchValue = 100.14399719238 -- Значение для поиска
local offset = 0xCC -- Смещение вниз (в байтах)
local minResults = 3 -- Минимальное количество результатов для заморозки (более 2)

function freezeIfMoreThanTwoAndNotZero()
    gg.setRanges(gg.REGION_C_ALLOC) -- Устанавливаем диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_FLOAT) -- Поиск значения

    local resultsCount = gg.getResultsCount()
    if resultsCount < minResults then
        gg.alert("Найдено менее " .. minResults .. " патронов (" .. resultsCount .. "). Заморозка не выполнена.")
        return
    end

    local results = gg.getResults(resultsCount)
    local frozenCount = 0

    for i = 1, resultsCount do
        local address = results[i].address + offset -- Адрес с учетом смещения
        local valueAtAddress = gg.getValues({{address=address, flags=gg.TYPE_DWORD}})[1].value

        if valueAtAddress > 0 then -- Замораживаем только если значение не равно нулю
            gg.addListItems({ -- Добавляем в список для заморозки
                {
                    address = address,
                    flags = gg.TYPE_DWORD,
                    freeze = true,
                }
            })
            frozenCount = frozenCount + 1
        end
    end

    if frozenCount > 0 then
        gg.toast("Заморожено " .. frozenCount .. " патронов.")
    else
        gg.alert("Нет патронов для заморозки (значения равны нулю).")
    end
end

freezeIfMoreThanTwoAndNotZero()
end
function antiperez() 
gg.clearResults() -- Очищаем результаты
local searchValue = 100.14399719238 -- Значение, которое нужно найти
local offset = 0xC8 -- Смещение вниз (в байтах)
local minResults = 2 -- Минимальное количество результатов для заморозки (более 2)

function freezeIfMoreThanTwo()
    gg.setRanges(gg.REGION_C_ALLOC) -- Устанавливаем диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_FLOAT) -- Поиск значения

    local resultsCount = gg.getResultsCount()
    if resultsCount < minResults then
        gg.alert("Найдено менее " .. (minResults) .. " патронов (" .. resultsCount .. "). Заморозка не выполнена.")
        return
    end

    local results = gg.getResults(resultsCount)

    for i = 1, resultsCount do
        local address = results[i].address + offset -- Адрес с учетом смещения
        gg.addListItems({ -- Добавляем в список для заморозки
            {
                address = address,
                flags = gg.TYPE_DWORD,
                freeze = true,
            }
        })
    end

    gg.toast("Заморожено " .. resultsCount .. " патронов.")
end

freezeIfMoreThanTwo()
    end
   function infiniteLoop()
        gg.setRanges(gg.REGION_OTHER)
        gg.searchNumber("1042536202", gg.TYPE_DWORD)
        gg.getResults(100)
        gg.editAll("1080099999", gg.TYPE_DWORD)
        gg.clearResults()
end
function offpr() 
    active = 0
main88 = gg.choice({
         " ⬅️ | Влево ",
         " ➡️ | Вправо  ", 
         " ❌ Выᴋᴧючиᴛь", 
                  }, nil, '')  
          if main88 == 1 then levo() end
          if main88 == 2 then pravo() end
          if main88 == 3 then offed() end
          end
          function levo() 
 gg.clearResults()
   local searchValue=77190601328179 
   local offset=0x18

   function Value()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=-1.0,
               }
           })
       end 

       gg.toast("Прицел смещен")
   end
   
   Value()
   end
   function pravo() 
   gg.clearResults()
   local searchValue=77190601328179 
   local offset=0x18

   function lue()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=1.0,
               }
           })
       end 

       gg.toast("Прицел смещен")
   end
   
   lue()
   end
   function offed() 
   gg.clearResults()
   local searchValue=77190601328179 
   local offset=0x18

   function ue()
       gg.setRanges(gg.REGION_CODE_APP)
       gg.searchNumber(searchValue,gg.TYPE_QWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=0.20,
               }
           })
       end 

       gg.toast("Прицел смещен")
   end
   
   ue()
  
end
function xy()
active = 0
main1717 = gg.choice({
         " ⬆️ | Смещерие X вперед на 2",
         " ⬇️ | Смещение X назад на 2", 
         " ➡️ | Смещение Y в право на 2",
         " ⬅️ | Смещение Y в лево  на 2", 
                  }, nil, '')  
          if main1717 == 1 then xper() end
          if main1717 == 2 then xnaz() end
          if main1717 == 3 then yprav() end
          if main1717 == 4 then ylev() end

          end
          function xper()
   x(2.0)
end 

function xnaz()
   x(-2.0)
end 

function x(addValue)
   local searchValue=-1083007583
   local offset=0x29C 

   function changeV()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue,gg.TYPE_DWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           local currentValue=gg.getValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
               }
           })[1].value 

           local newValue=currentValue+addValue 

           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=newValue,
               }
           })
       end 

       if addValue>0 then 
           gg.toast ("Вы были смещены на 2 по координате X") 
       else 
           gg.toast ("Вы были смещены на 2 по координате X") 
       end  
   end

   changeV()
   end
   function yprav()
   ycord(2.0)
end 

function ylev()
   ycord(-2.0)
end 

function ycord(addValue)
   local searchValue=-1083007583
   local offset=0x2A0

   function changalue()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue,gg.TYPE_DWORD)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           local currentValue=gg.getValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
               }
           })[1].value 

           local newValue=currentValue+addValue 

           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=newValue,
               }
           })
       end 

       if addValue>0 then 
           gg.toast ("Вы были смещены по координате Y") 
       else 
           gg.toast ("Вы были смещены по координате Y") 
       end  
   end

   changalue()
   end
   function povor()
   active = 0
main8118 = gg.choice({
         " ✅ Вᴋᴧючиᴛь ", 
         " ❌ Выᴋᴧючиᴛь", 
                  }, nil, '')  
          if main8118 == 1 then onedd() end
          if main8118 == 2 then offedd() end
          end
          function onedd()
          gg.clearResults()
   local searchValue=100.14399719238     
   local offset=0x1C

   function cgeValue()
       gg.setRanges(gg.REGION_C_ALLOC)
       gg.searchNumber(searchValue,gg.TYPE_FLOAT)

       local results=gg.getResults(gg.getResultsCount())

       if #results==0 then return end 

       for i=1,#results do 
           local address=results[i].address+offset
            
           gg.setValues({
               {
                   address=address,
                   flags=gg.TYPE_FLOAT,
                   value=532.7,
               }
           })
       end 

       gg.toast("Быстрые повороты активированы")
   end
   
   cgeValue()
   end
   function offedd()
      gg.setRanges(gg.REGION_C_ALLOC) -- Установить диапазон поиска
gg.searchNumber("532.7", gg.TYPE_FLOAT) -- Поиск значения 9999991
local results = gg.getResults(100) -- Получить результаты поиска
for i = 1, #results do
    results[i].value = 7.5 -- Изменить найденные значения на 20
end
gg.setValues(results) -- Применить изменения
gg.toast("Резкие повороты выключены") -- Показать уведомление
   end
  
   function kosm()
   gg.clearResults()  -- Очищаем результаты
local searchValue = 404750497 -- Значение, которое нужно найти
local offset = 0x48 -- Смещение вниз (в байтах)
local newValue = 10.0 -- Значение, на которое нужно изменить

function kosmo()
    gg.setRanges(gg.REGION_C_ALLOC) -- Установите диапазон поиска
    gg.searchNumber(searchValue, gg.TYPE_DWORD) -- Поиск значения

    local results = gg.getResults(gg.getResultsCount()) -- Получаем результаты поиска

    if #results == 0 then
        gg.alert("Значение не найдено.")
        return
    end

    for i = 1, #results do
        local address = results[i].address + offset -- Вычисляем адрес с учетом смещения вниз
        
        -- Устанавливаем новое значение на 9999
        gg.setValues({
            {
                address = address,
                flags = gg.TYPE_FLOAT,
                value = newValue,
            }
        })
    end

    gg.toast("Машина отправлена в космос") 
end
kosmo() 
end
function exit()
   os.exit()
end 

local active= false

while true do 
   if gg.isVisible(true) then    
       active=true    
       gg.setVisible(false)    
   end    
   
   if active==true then     
       menu()
       active=false -- сбрасываем флаг после вызова меню чтобы не зацикливать вызов  
   end    
end
