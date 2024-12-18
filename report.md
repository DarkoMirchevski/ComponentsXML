# Packaged Components Code Quality Report
|#|Component Name|Component ID|Version|Type|Issue|Issue Type|Priority|
|---|---|---|---|---|---|---|---|
|1|[New [HTTP] Client Connector Operation](Report/Training-Darko-Mirchevski/Doubleservice/New [HTTP] Client Connector Operation.xml)|00150a3b-41e3-4df8-9948-a8d7e14930ed|3|connector-action|Component names must not start with "New " which is Boomi"s default. They should be named to have a accurate description.|CODE_SMELL|MINOR|
|2|[New Map](Report/Training-Darko-Mirchevski/Doubleservice/New Map.xml)|25aa855a-68b5-41b4-bc52-b676eb01f7ba|1|transform.map|Component names must not start with "New " which is Boomi"s default. They should be named to have a accurate description.|CODE_SMELL|MINOR|
|3|[Test2](Report/Training-Darko-Mirchevski/Doubleservice/Test2.xml)|37c02881-94c2-4217-b133-8a8d23e2b78a|26|process|Is the password hard coded? The connection property password must be marked as extensible.
            |BUG|MAJOR|
|4|[Test2](Report/Training-Darko-Mirchevski/Doubleservice/Test2.xml)|37c02881-94c2-4217-b133-8a8d23e2b78a|26|process|Is the URL hardcoded? URL property used in connection must be marked as extensible.
            |BUG|MAJOR|
|5|[Test2](Report/Training-Darko-Mirchevski/Doubleservice/Test2.xml)|37c02881-94c2-4217-b133-8a8d23e2b78a|26|process|Is user name hard coded? Connection setting username must be marked as extensible.
            |BUG|MAJOR|
