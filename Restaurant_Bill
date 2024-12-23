#include <stdio.h>
#include<time.h>
void menu();


int main() {
    time_t t;   
    time(&t);

    int price=0;
    int samosa=0,sandwich=0,burger=0,fries=0,pasta=0;
    int tea=0,coffee=0,masalasoda=0,badamshake=0,oreoshake=0;
    int pastry=0,muffins=0,donuts=0,chocolava=0,waffle=0;
    menu();
    
    int flag=1;

    while(flag!=0){
        int quantity;
        int item;
        printf("\nEnter the serial no of item you want to order: ");
        scanf("%d",&item);
        printf("Enter the Quantity: ");
        scanf("%d",&quantity);
        switch(item){
            case 1: price=price+20*quantity;
                    samosa+=quantity;
                    break;

            case 2: price=price+50*quantity;
                    sandwich+=quantity;
                    break;
                    
            case 3: price=price+70*quantity;
                    burger+=quantity;
                    break;
                    
            case 4: price=price+70*quantity;
                    fries+=quantity;
                    break;
                    
            case 5: price=price+90*quantity;
                    pasta+=quantity;
                    break;
                    
            case 6: price=price+10*quantity;
                    tea+=quantity;
                    break;
                    
            case 7: price=price+15*quantity;
                    coffee+=quantity;
                    break;
                    
            case 8: price=price+30*quantity;
                    masalasoda+=quantity;
                    break;                    
                           
            case 9: price=price+50*quantity;
                    badamshake+=quantity;
                    break;
                       
            case 10: price=price+70*quantity;
                     oreoshake+=quantity;
                     break;
                         
            case 11: price=price+40*quantity;
                     pastry+=quantity;
                     break;
                         
            case 12: price=price+50*quantity;
                     muffins+=quantity;
                     break;
                         
            case 13: price=price+60*quantity;
                     donuts+=quantity;
                     break;
                         
            case 14: price=price+70*quantity;
                     chocolava+=quantity;
                     break;
                         
            case 15: price=price+80*quantity;
                     waffle+=quantity;
                     break; 
            default: printf("Please choose an item from the Menu");
                     break;                        
        
        }
        printf("\nIf you Want to Order more press any numeric key or else 0 to get your Bill: ");
        scanf("%d",&flag);
    }
    
    printf("\n            Carpeedium           \n");
    printf("             Pure Veg            \n");
    printf("         Banglore-560050         \n");
    printf("***********TAX INVOICE***********\n");
    printf(" Date: %s", ctime(&t));
    printf("          Bill No: 69          \n");
    printf("---------------------------------\n");
    printf("Item        Quantity       Amount\n");
    printf("---------------------------------\n");
    if (samosa!=0){
    printf("Samosa          %d          Rs.%d\n",samosa,20*samosa);
    }
    
    if (sandwich!=0){
    printf("Sandwich        %d          Rs.%d\n",sandwich,50*sandwich);
    }
    
    if (burger!=0){
    printf("Burger          %d          Rs.%d\n",burger,70*burger);
    }

    if (fries!=0){
    printf("Fries           %d          Rs.%d\n",fries,70*fries);
    }
    
    if (pasta!=0){
    printf("Pasta           %d          Rs.%d\n",pasta,90*pasta);
    }
    
    if (tea!=0){
    printf("Tea             %d          Rs.%d\n",tea,10*tea);
    }
    
    if (coffee!=0){
    printf("Coffee          %d          Rs.%d\n",coffee,15*coffee);
    }
    
    if (masalasoda!=0){
    printf("Masala Soda     %d          Rs.%d\n",masalasoda,30*masalasoda);
    }
    
    if (badamshake!=0){
    printf("Badam Shake     %d          Rs.%d\n",badamshake,50*badamshake);
    }
    
    if (oreoshake!=0){
    printf("Oreo Shake      %d          Rs.%d\n",oreoshake,70*oreoshake);
    }

    if (pastry!=0){
    printf("Pastry          %d          Rs.%d\n",pastry,40*pastry);
    }

    if (muffins!=0){
    printf("Muffins         %d          Rs.%d\n",muffins,50*muffins);
    }
    
    if (donuts!=0){
    printf("Donuts          %d          Rs.%d\n",donuts,60*donuts);
    }
    
    if (chocolava!=0){
    printf("Chocolava       %d          Rs.%d\n",chocolava,70*chocolava);
    }
    
    if (waffle!=0){
    printf("Waffle          %d          Rs.%d\n",waffle,80*waffle);
    }
    float tax_price=0.025*price;
    int total=2*tax_price+price;
    printf("---------------------------------\n");
    printf("             Sub Total  : Rs.%d\n",price);
    printf("SGST.27AAFHK4833  @2.5%% : Rs.%.1f\n",tax_price);
    printf("CGST.27AAFHK4833  @2.5%% : Rs.%.1f\n",tax_price);
    printf("---------------------------------\n");
    printf("                  Total : Rs.%d\n",total);
    printf("---------------------------------\n");
    printf("\n     Thank You, Visit Again!     \n");
    printf("\n---------------------------------\n");
    return 0;
}

void menu(){
    printf("\n                             CARPEEDIUM                            \n");
    printf("\n********************************ITEMS******************************\n");
    printf("\n      Snacks                Beverages                  Dessert  \n");
    printf("\n1.Samosa   Rs.20       6.Tea          Rs.10       11.Pastry    Rs40");
    printf("\n2.Sandwich Rs.50       7.Coffee       Rs.15       12.Muffins   Rs50");
    printf("\n3.Burger   Rs.70       8.Masala Soda  Rs.30       13.Donuts    Rs60");
    printf("\n4.Fries    Rs.70       9.Badam Shake  Rs.50       14.Chocolava Rs70");
    printf("\n5.pasta    Rs.90       10.Oreo Shake  Rs.70       15.Waffle    Rs80\n");
    printf("\n*******************************************************************\n");
}
