```php
<?php

declare(strict_types=1);

namespace HtunHtunHtet;

final class About extends Me 
{
    public string $fullName = 'Htun Htun Htet';
    
    public string $nickName = 'Ryan';
    
    public function yourNameIsHardToPronounce(): string
    {
        return $this->nickName;
    }

    public function getMyKnowledges(): array
    {
        return [
            PHP::class,
            Symfony::class,
            Laravel::class,
            React::class,
            Typscript::class,
            Javascript::class,
            Aws::class,
        ];
    }
}
```
