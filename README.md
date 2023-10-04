```php
<?php

declare(strict_types=1);

namespace SoftwareEngineer;

final class AboutMe extends HtunHtunHtet 
{
    public string $fullName = 'Htun Htun Htet';
    
    public string $nickName = 'Ryan';
    
    public function yourNameIsHardToPronounce(): string
    {
        return $this->nickName;
    }

    /**
     * @return string []
     */
    public function getKnowledge(): array
    {
        return [
            PHP::class,
            Symfony::class,
            Laravel::class,
            React::class,
	    Vue::class,
            Typscript::class,
            Aws::class,
            Docker::class,
        ];
    }
    
    /**
     * @return array<string, string>
     */
    public function getAttributes(): array
    {
        return [
            'Current Company' => 'Global Software Solutions Corp' ,
            'Position' => 'Senior Full Stack Developer',
        ];   
    }
    
    public function getYearsOfExperiences(): int
    {
        return 10;    
    }
}
```
