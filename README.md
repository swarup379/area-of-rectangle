class rectangle:
    def idata(self):
        rectangle.length=int(input())
        rectangle.breadth=int(input())
    def odata(self):
        print("the length of rectangle:",rectangle.length)
        print("the breadth of rectangle:",rectangle.breadth)
    def area(self):
        print((rectangle.length)*(rectangle.breadth))
obj=rectangle()
obj.idata()
obj.odata()
obj.area()
