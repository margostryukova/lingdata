для извлечения временных меток и токенов:words@(\w+)\s@\w+\s(\d{2}:\d{2}:\d{2}\.\d{3})\s\d+\.\d+\s(\d{2}:\d{2}:\d{2}\.\d{3})\s\d+\.\d+\s\d+\.\d+\s\d+\.\d+\s(.+)
для лемм:(.+?)\{(.+?)=(.+?)\}
для морфологических признаков:(.+?)\{(.+?)=(.+?)\}

Одна из проблем инструмента mystem заключается в частотном отсутствии заглавных букв у имен собственных, хотя ближе к середине файда они уже определяются верно.
Не уверена, можно ли зацепиться за то, что форма причастия определяется как глагол в инфинитиве, но заметила это.