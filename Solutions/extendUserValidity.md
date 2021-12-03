## inside the user component add those line of codes
## 'enableAutoLogin' => false,'authTimeout' => 30000
## you will get somthimg like that 
 'user' => [
            'identityClass' => 'app\models\User',
            'enableAutoLogin' => false,
            'authTimeout' => 30000,
        ],