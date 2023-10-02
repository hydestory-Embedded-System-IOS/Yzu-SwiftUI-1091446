<h1>HW1</h1>
    
```swift
import SwiftUI

    struct ContentView: View{
     var body: some View{
         Image("Pic02")
            .resizable()
            .aspectRatio(contentMode: .fit)
            .overlay(
                Text("朱品諴")
                    .fontWeight(.heavy)
                    .lineSpacing(20)
                    .font(.system(size: 32.0))
                ,
                alignment: .topLeading
            )
            .overlay(
                Text("1091446")
                    .fontWeight(.heavy)
                    .lineSpacing(20)
                    .font(.system(size: 32.0))
                ,
                alignment: .topTrailing
            )
            .overlay(
                Text("Stay Foolish")
                    .fontWeight(.heavy)
                    .lineSpacing(20)
                    .font(.system(size: 32.0))
                    .foregroundColor(.white)
                    .frame(width: 350, height: 150, alignment: .center)
                    .background(Color.blue)
                    .cornerRadius(30.0)
                    .opacity(0.8)
                    .overlay(
                        Image(systemName: "paperplane")
                            .font(.system(size: 32.0))
                        ,
                        alignment: .bottom
                    ),
                alignment: .bottom
            )
            
    }

    }

```

<img width="40%"  src="https://raw.githubusercontent.com/hydestory/Yzu-SwiftUI-1091446/main/IMG_0332.jpeg">
