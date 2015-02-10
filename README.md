# IQIWebAlertView
A class that simulates an UIAlertView, but using a web view to display content.

Installing
----------
You could clone the whole repository and drag the project to an Xcode workspace.

Usage
-----
Displaying an alert:

    IQIWebAlertView *alert = [[IQIWebAlertView alloc]initWithTitle:@"My title" andFrame:CGRectMake(0, 0, 200, 200)];
    [alert addConfirmationButton:@"OK"];
    [alert showAlertWithHTMLText:@"HTML TEXT" inView:self.view];

Customization
-----
You can customize the components, simply by accessing the properties.


Author & License
----------------

Licensed under the terms of the [MIT License][mit]:

Copyright © Paolo Musolino, <info@codeido.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

The software is provided “as is”, without warranty of any kind, express or
implied, including but not limited to the warranties of merchantability,
fitness for a particular purpose and noninfringement. In no event shall the
authors or copyright holders be liable for any claim, damages or other
liability, whether in an action of contract, tort or otherwise, arising from,
out of or in connection with the Software or the use or other dealings in
the Software.

[mit]: http://www.opensource.org/licenses/mit-license.php
