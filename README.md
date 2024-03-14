# Hi! I'm Soufiyane 👋

```php
<?php

namespace soufiyane;

class About extends Me
{
    public function __construct()
    {
        echo "PHP/Symfony Engineer";
    }

    public function getPersonalInfo(): array
    {
        return [
            'name' => 'soufiyane',
            'location' => 'Marrakech, Morocco',
            'interests' => [
                'Symfony (PHP Framework)',
                'Cloud Computing'
            ],
        ];
    }
}

$soufiyane = new About();

