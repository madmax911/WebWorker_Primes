# WebWorker_Primes
Using a single file, web worker calculates n primes without blocking the main thread.

This means no separate .js file is necessarily required to get a webworker going.
Thus, it can operate in the sandbox of a single file and therefor not run into any
CORS issues.  This is useful when used for standalone serverless unhosted purposes.
You should be able to download this and run it locally from your hard drive - or your
smart phone.
