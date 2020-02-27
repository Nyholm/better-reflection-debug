
```
▶ docker run --rm -v `pwd`:/app nyholm/roave-bc-check
Detected last minor version: 1.0.0
Comparing from 2ed9ad978a29467dadef17eccfc911b0dc23c379 to f21befd57338d19b49db4ee827635917a7f044c1...
Loading composer repositories with package information
Installing dependencies from lock file
Package operations: 1 install, 0 updates, 0 removals
  - Installing psr/log (1.1.2): Loading from cache
Loading composer repositories with package information
Installing dependencies from lock file
Package operations: 1 install, 0 updates, 0 removals
  - Installing psr/log (1.1.2): Loading from cache
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source
[BC] SKIPPED: Roave\BetterReflection\Reflection\ReflectionClass "PHPUnit\Framework\TestCase" could not be found in the located source

In IdentifierNotFound.php line 30:
                                                                               
  Roave\BetterReflection\Reflection\ReflectionClass "Psr\Log\Test\DummyTest"   
  could not be found in the located source                                     
                                                                               

roave-backwards-compatibility-check:assert-backwards-compatible [--from [FROM]] [--to TO] [--format [FORMAT]]

```