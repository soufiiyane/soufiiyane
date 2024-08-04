# Hi! I'm Soufiyane 👋

```php
<?php

namespace soufiyane;

class About extends Me
{
    public function __construct()
    {
        echo "Certified Cloud Engineer";
    }

    public function getPersonalInfo(): array
    {
        return [
            'name' => 'soufiyane',
            'location' => 'Marrakech, Morocco',
            'interests' => [
                'AWS Cloud Computing',
                'PHP/Symfony',
                'JavaScript/React.JS'
            ],
        ];
    }
}

$soufiyane = new About();

