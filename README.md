# Upper-Lower-case-generator
The below code will generate UpperCase to LowerCase without using ascii code
function utol() {
    var value = document.getElementById('value').value
    var str = ''
    var display = document.getElementById('display')
    for (let i = 0; i <= value.length - 1; i++) {
        let cap = value[i].toUpperCase()
        console.log(value[i].charCodeAt())
        if (value[i] === cap) {
            str += value[i].toLowerCase()
        }
        else {
            str += value[i].toUpperCase()
        }
    }
    display.innerHTML = str
}
