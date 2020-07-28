```php
<?php

namespace LucasPanao;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Objetivo School',
                'position' => 'System Programmer Jr.'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Python::class,
            Php::class,
            Javascript::class,
            Bootstrap::class,
            Vuejs::class,
            AngularJs::class,
            Nodejs::class,
            MySql::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
