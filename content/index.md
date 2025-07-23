#### Основное

- [[В чеках разнится время]]
- [[Настройка передачи чеков в офд]]
- [[Не пропечатался чек о закрытии или открытии смены]]
- [[Обновление или установка драйвера]]
- [[Переподключение эквайринга]]

<script type="text/javascript" >
function Copy(containerid) {
	    let textarea = document.createElement('textarea');
	    textarea.id = 'temp';
	    textarea.style.height = 0;
	    document.body.appendChild(textarea);
	    textarea.value = document.getElementById(containerid).innerText;
	    let selector = document.querySelector('#temp');
	    selector.select();
	    document.execCommand('copy');
	    document.body.removeChild(textarea);
}
</script>

<button onclick="Copy('toCopy')" title="Copy">Copy</button>

<div id="toCopy">text to copy!</div>
