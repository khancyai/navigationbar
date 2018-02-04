#### Set navigation bar tint / background colour
UINavigationBar.appearance().barTintColor = UIColor.redColor()

#### Set Navigation bar Title colour
UINavigationBar.appearance().titleTextAttributes = [NSForegroundColorAttributeName:UIColor.whiteColor()]

#### Set navigation bar ItemButton tint colour
UIBarButtonItem.appearance().tintColor = UIColor.yellowColor()

#### Set Navigation bar background image
let navBgImage:UIImage = UIImage(named: “bg_blog_navbar_reduced.jpg”)!
UINavigationBar.appearance().setBackgroundImage(navBgImage, forBarMetrics: .Default)

#### Set navigation bar Back button tint colour
UINavigationBar.appearance().tintColor = UIColor.whiteColor()

or you can also access UINavigationBar through the UINavigationController and change UINavigationBar tint color For example:

#### Set navigation bar background colour
self.navigationController!.navigationBar.barTintColor = UIColor.yellowColor()

#### Set navigation bar title text colour
self.navigationController!.navigationBar.titleTextAttributes = [NSForegroundColorAttributeName: UIColor.blackColor()]

#### Set Navigation bar background Image
let navBgImage:UIImage = UIImage(named: “image.jpg”)!
self.navigationController!.navigationBar.setBackgroundImage(navBgImage,
forBarMetrics: .default)
