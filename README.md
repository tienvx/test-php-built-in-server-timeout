# Test PHP Built-in Server Timeout

This project trying to fix this error:

```
1) PhpPactTest\Standalone\ProviderVerifier\VerifierTest::testVerify
Symfony\Component\Process\Exception\ProcessTimedOutException: The process "php -S 127.0.0.1:7202 -t "D:\a\pact-php\pact-php\tests\PhpPact\Standalone\ProviderVerifier/../../../_public/"" exceeded the timeout of 60 seconds.

D:\a\pact-php\pact-php\vendor\symfony\process\Process.php:1263
D:\a\pact-php\pact-php\vendor\symfony\process\Process.php:468
D:\a\pact-php\pact-php\tests\PhpPact\Standalone\ProviderVerifier\VerifierTest.php:25
```
