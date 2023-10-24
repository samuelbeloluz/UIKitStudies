Making Connections

Opening the Storyboard Code - First, click on the rectangular area on the phone screen being developed. Click on the 'ViewController' button on the right, go to the development area in the top right corner, choose the 'Adjust editor options' option. When you click on it, in the dropdown menu, select 'Assistant,' and this will open the code for our View, next to the Storyboard, allowing for programmatic interface configurations. (If Xcode doesn't open, there's another option.)

2nd Option - Go to the hierarchical file tree, navigate to the desired file you want to open, hold down the 'option' key on the keyboard and click on the desired code.

Tip: To find where the class begins and ends (or other items), click on the brace that marks the entire body of it.

IBOutlets are references to elements in a Storyboard in the code to change the characteristics of an element. To create an IBOutlet (a connection) for an element in the code, right-click on the element, drag it to the code, and it needs to be within the view controller's class to work. This way, we can establish a connection in the code and program its characteristics. (Always place IBOutlet connections above the 'viewDidLoad()' function.) To remove the connection, right-click on the element, and there will be an 'x' to remove the connection from the code. Simply deleting the line in the code that references the connection is not enough.

Pro Tip: Do not configure the characteristics of an element through inspectors. It's ideal to set up the element programmatically. Always keep IBOutlet connections above 'viewDidLoad()'.

Note: When what is in the Storyboard conflicts with what is in the code, the code takes precedence, as long as that element doesn't have a programmatic connection.

With our connections established, within the 'viewDidLoad()' function, we can change the characteristics of our elements. Whenever we use IBOutlets to change the characteristics of an element, we do it within the 'viewDidLoad()' function.

IBActions are used to modify the actions of desired elements. To create an IBAction connection, it's similar to IBOutlets, but the 'connection' is set as 'action'. For IBAction connections, it's a good practice to keep them below the 'viewDidLoad()' function.

Naming Connections: To name connections, regardless of the type of connection, we use camelCase normally, but the last word of the name should represent what it is, as an example: Label, TextField, Button, etc... For instance, if you have a TextField you want to name 'password,' then the connection name would be 'passwordTextField.'

Tip: Use 'command+R' to rebuild the code or click on the button next to the play button that appears when the code is running. Use 'command+B' to start the code Build.

Shortening Types: When you're writing code and the compiler already knows what type will be used, you can omit it to make the code cleaner and more concise. For example, instead of 'view.backgroundColor = UIColor.purple,' since the compiler expects a UIColor as a response for a backgroundColor, you can simply write it as 'view.backgroundColor = .purple.'
