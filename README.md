# index
<html>
<body>
<script>
var xhr = new XMLHttpRequest();
xhr.open('GET', 'https://scribie.com/sensitive-data', true);
xhr.onload = function() {
    if (xhr.status === 200) {
        document.write(xhr.responseText);
    }
};
xhr.send();
</script>
</body>
</html>
