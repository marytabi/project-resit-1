<?php
$current_file = basename($_SERVER['PHP_SELF']);

switch ($current_file) {
    case 'indexFR.php':
        $current_lang = 'fr';
        $current_lang_text = 'FR';
        break;
    
    default:
        $current_lang = 'en';
        $current_lang_text = 'EN';
        break;
}

$lang_options = [
    'en' => ['text' => 'EN', 'page' => 'menu.php'],
    'fr' => ['text' => 'FR', 'page' => 'menuFR.php'],
    
];

unset($lang_options[$current_lang]);
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>