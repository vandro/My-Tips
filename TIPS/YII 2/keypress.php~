<?php 



$js = <<<JS
	$('form input').on('keypress', function(e) {
        // console.log("3333");
        return e.which !== 13;
    });

JS;
$this->registerJs($js);

/*				OR					*/

$js = <<<JS
    $('#w0').on('keyup keypress', function(e) {
    var keyCode = e.keyCode || e.which;
    if (keyCode === 13) {
    e.preventDefault();
    return false;
    }
    });

JS;
$this->registerJs($js);