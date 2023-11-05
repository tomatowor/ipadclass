<h1>hw2</h1>

```swift

import SwiftUI
struct ContentView: View{
    @State var count:Int = 0
    var body: some View{
        VStack{
            if count == 0{
                Text("準備")
                    .padding(.all,10)
                    .font(.system(size: 50))                   
                    .foregroundColor(.white)
                    .cornerRadius(20)                    
            }
            if count == 1{
                Text("石頭")
                    .padding(.all,10)
                    .font(.system(size: 50))                   
                    .foregroundColor(.white)
                .cornerRadius(20)               
                
            }
            if count == 2{
                Text("剪刀")
                    .padding(.all,10)
                    .font(.system(size: 50))                   
                    .foregroundColor(.white)
                    .cornerRadius(20)               
                
            }
            if count == 3{
                Text("布")
                    .padding(.all,10)
                    .font(.system(size: 50))                   
                    .foregroundColor(.white)
                    .cornerRadius(20)               
                
            }   
            Button(action: {
                count = Int.random(in: 1..<4)
            }, label: {
                Text("猜拳！")
                    .padding(.all,10)
                    .frame(width: 300, height: 100, alignment: .center)
                    .font(.system(size: 50))
                    .background(Color.red)
                    .foregroundColor(.white)
                    .border(Color.red, width: 5)
                    .cornerRadius(20)
            })
            
        }
    }
}



```

<img src="https://raw.githubusercontent.com/tomatowor/ipadclass/main/720909355.515452.gif">
