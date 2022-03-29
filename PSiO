#include <iostream>
#include <vector>
#include <algorithm>
#include <list>
#include <iterator>

enum class TypRosliny { Owoc, Warzywo };

struct Roslina {
    TypRosliny typ;
    std::string nazwa;
};

    using Koszyk = std::vector<Roslina>;

    Koszyk koszyk;


    std::ostream& operator<<(std::ostream &out, const Roslina &roslina)
    {
    return out << "typ rosliny: " << static_cast<int>(roslina.typ) << ", nazwa: " << roslina.nazwa << '\n';
    }



    template <typename T>
    void print(const std::vector<T> &jakasnazwa) {
        for (auto x : jakasnazwa) {
            std::cout << x << '\n';
        }
    }


    void wyswietl()
    {
        std::vector<Roslina> koszyczek={{TypRosliny::Owoc,"Banan"}, {TypRosliny::Warzywo,"Pomidor"}, {TypRosliny::Owoc,"Pomarancza"}
    };


    print(koszyczek);

    }

    int main() {



        wyswietl();

    }
