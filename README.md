# ParseLogIn-SignIn-SwiftDemo
This is the ParseUI Login, and Signup controller implemented in Swift

I have a hard time finding Swift example code that works with the Parse SDK.

Finding a fully implemented PFLoginController example in Swift was getting to be a hassle.

So I am creating one.


The key for me is to implement the SignUp controller method to dismiss the view when a user initially signs up.

func logInViewController(logInController: PFSignUpViewController!, didLogInUser user: PFUser!) {
      self.dismissViewControllerAnimated(false, completion: nil)
}

Keep on Truck'n






