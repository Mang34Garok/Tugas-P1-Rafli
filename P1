#include <iostream>
#include <string>

class Person {
    private:
        std::string nama;
  public:
        Person () {
       std::cout << "Aku Telah Lahir Didunia" << std::endl;
    }
    
        Person (const std::string nama) {
        std::cout << "manusia bernama "  << nama << " telah lahir" << std::endl;
        this->nama = nama;
    }   
    
        void introduce() {
            std::cout <<"Halo Nama saya " << this->nama << std::endl;
        }
    std::string getnama() {
        return this-> nama;
    }
        void introduce(Person obj) {
            std::string yudhi = obj.getnama();
            std::cout <<"Halo" << yudhi << "nama saya adalah: " << this->nama<< std::endl; 
        }
 
};  
   
   int main() {
       Person Hitler;
       Person Hitler2("Hitler");
       Hitler2.introduce();
       Person Hitler3("Yudhi");
       Hitler2.introduce(Hitler 3);
   
       return 0;
   }
       
