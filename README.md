# Useful_things

expr -l objc++ -O -- [[UIWindow keyWindow] _autolayoutTrace]
// with this line print the entire tree of UI


expr -l Swift -- import UIKit
expr -l Swift -- unsafeBitCast(0x7f88a8cc2050, to: UIView.self).backgroundColor = UIColor.red
// With this I put a red background to the view with the error in this case 0x7f88a8cc2050 of UIView 
// type, but cuold it be any View
