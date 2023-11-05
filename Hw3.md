<h1>hw3</h1>

```swift
import SwiftUI
struct ContentView:View{
    var body:some View{
        
        ZStack{
            Image("Back")
                .resizable()
            VStack(spacing:120){
                HStack(spacing:40){
                    TomatoView()
                    BananaView()
                    GuavaView()
                }
                .padding(.top, 70)
                HStack(spacing:40){
                    pic1View()
                    pic2View()
                    pic3View()
                }
                .padding(.leading, 0)
                HStack(spacing:40){
                    pic4View()
                    pic5View()
                    pic6View()
                }
                .padding(.bottom,-50)
            }
            
        }
    }
}
struct TomatoView: View {
    var body: some View {
        VStack {
            Image("Conti")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2,alignment: .center)
                .position(CGPoint(x: 115.0, y: 90.0))
            /* 
             Text("tomato")
             .fontWeight(.bold)
             .font(.system(size: 0))*/
        }
    }
}
struct BananaView:View{
    var body:some View{
        VStack{
            Image("Mikasa ")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: 55, y: 90)
        }
    }
}
struct GuavaView:View{
    var body:some View{
        VStack{
            Image("Molten")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(CGPoint(x: 8.0, y: 90.0))
            
        }
    }
}
struct pic1View:View{
    var body:some View{
        VStack{
            Image("Pic1")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: 115, y: 50.0)
        }
    }
}
struct pic2View:View{
    var body:some View{
        VStack{
            Image("Pic2")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: /*@START_MENU_TOKEN@*/.center/*@END_MENU_TOKEN@*/)
                .position(x: 50, y: 50.0)
        }
    }
}
struct pic3View:View{
    var body:some View{
        VStack{
            Image("Pic3")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: 10.0, y: 50.0)
        }
    }
}
struct pic4View:View{
    var body:some View{
        VStack{
            Image("Pic4")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: 115, y: -40)
        }
    }
}
struct pic5View:View{
    var body:some View{
        VStack{
            Image("Pic5")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: 55, y: -40)
        }
    }
}
struct pic6View:View{
    var body:some View{
        VStack{
            Image("Pic6")
                .resizable()
                .aspectRatio( contentMode: .fit)
                .frame(width: UIScreen.screenWidth/12-2,height: UIScreen.screenHeight/12-2, alignment: .center)
                .position(x: /*@START_MENU_TOKEN@*/10.0/*@END_MENU_TOKEN@*/, y: -40)
        }
    }
}
extension UIScreen{
    static let screenWidth=UIScreen.main.bounds.size.width
    static let screenHeight=UIScreen.main.bounds.size.height
    static let screensize=UIScreen.main.bounds.size
}





```
<img src="https://raw.githubusercontent.com/tomatowor/ipadclass/main/hw2screen.jpg">
