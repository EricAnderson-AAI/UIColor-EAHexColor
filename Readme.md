<p align="center">
  <img style="width:300px;height:300px;" src="https://raw.githubusercontent.com/EricAnderson-AAI/UIColor-EAHexColor/master/xcode-icon.png">
</p>

UIColor+EAHexColor
=================
An Objective-C category for creating a UIColor using an RGBA hex string.

    self.view.backgroundColor = [UIColor colorWithHex:@"#FFF"]; // Supports 3 characters
    
    uiTextField.layer.borderColor = [UIColor colorWithHex:@"#4477"].CGColor; // Supports 4 characters
    
    uiTextField.layer.borderColor = [UIColor colorWithHex:@"#171926AA"].CGColor; // Color with alpha
