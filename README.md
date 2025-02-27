let x = prompt("enter your number ");
const y = prompt("enter secod number"); 
const z = prompt("enter your choice ");
function calc(x,y,z)
{
    switch(z)
    {
        case "+":
            return x+y;
            break;
         case "-":
                return x-y;
                break;
            case "*":
                return x*y;
                break;
            case "/ BB":
                return x/y;
                break;
  default:
    return z;
    }
}
let valueof = calc(x,y,z);
console.log("value of ",z,"is",valueof );
