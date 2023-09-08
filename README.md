# Hi! I'm Soufiyane 👋
```php
<?php

namespace soufiyane;

class About extends Me
{
    public function __construct()
    {
        echo "Software Engineer Student 4th Year";
    }

    public function getPersonalInfo(): array
    {
        return [
            'name' => 'soufiyane',
            'title' => 'Software Enginner',
            'location' => 'Marrakech, Morocco',
            'interests' => [
                'React.js',
                'Symfony (PHP Framework)',
            ],
            'workplace' => [
                            'company' => 'TechMyTeam',
                            'position' => 'Web Developer'         
                        ],
            'currentLearning' => 'AWS (Amazon Web Services)', 'Quality Assurance (QA)'
        ];
    }

    public function getSkills(): array
    {
        return [
          'Front-end' => [
              'JavaScript' => ['React', 'Redux', 'Stimulus', 'Jest', 'Cypress'],
          ],
          'Back-end' => [
              'PHP' => ['Symfony', 'ApiPlatform', 'Turbo', 'PHPUnit'],
          ],
          'Development Tools' => ['npm', 'Yarn', 'Webpack', 'Docker'],
          'Databases' => ['MongoDB', 'MySQL', 'SQLite', 'Oracle'],
      ];
    }

}

$soufiyane = new About();
```
