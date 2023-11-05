<h1>HW1</h1>
```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        ZStack{
            Image("Photo")
                .resizable()
                .scaledToFill()
            Text("劉宗翰")
                .font(.title)
                .frame(width: 150, height: 70, alignment: .center)
                .background(Color.primary)
                .cornerRadius(40)
                .position(x: 155, y: 80)
                .foregroundStyle(LinearGradient(
                    colors: [.black],
                    startPoint: .leading,
                    endPoint:.trailing
                ))
                .opacity(0.48)
                .bold()            
            Text("1103322")
                .font(.title)
                .frame(width: 150, height: 70, alignment: .center)
                .background(Color.primary)
                .cornerRadius(40)
                .position(x: 155, y: 160)
                .foregroundStyle(LinearGradient(
                    colors: [.black],
                    startPoint: .leading,
                    endPoint:.trailing
                ))
                .opacity(0.48)
                .bold()        
            
            Text("排球")
                .font(.title)
                .frame(width: 150, height: 70, alignment: .center)
                .background(Color.primary)
                .cornerRadius(40)
                .position(x: 155, y: 240)
                .foregroundStyle(LinearGradient(
                    colors: [.black],
                    startPoint: .leading,
                    endPoint:.trailing
                ))
                .opacity(0.48)
                .bold()          
            Image(systemName: "figure.volleyball")
                .foregroundStyle(LinearGradient(
                    colors: [.black],
                    startPoint: .leading,
                    endPoint:.trailing
                ))
                .font(.system(size: 30))
                .position(x:203, y: 240)    
                .opacity(0.48)
        }
        .overlay(
            Text("天才是1%的天賦加上99%的努力")
                .font(.system(size:20))
                .bold()
                .frame(width: 350, height: 50, alignment: .center)
                .foregroundStyle(LinearGradient(
                    colors: [.black],
                    startPoint: .leading,
                    endPoint:.trailing
                ))
                .background(Color.primary)
                .opacity(0.70)
                .cornerRadius(10)
            ,
            alignment: .bottom
        )
    }
}
```
