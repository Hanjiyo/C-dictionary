#include <iostream> 
#include <string> 

using namespace std;

int main(){
  string input;
  cout << "Define: ";
  cin >> input;

  if (input == "Abacus")
    cout << "a wooden rack that has meyal rods with beads mounted on them" << endl;
  else if (input == "Napier's_Bones")
    cout << "the first mechanical calculating device" << endl;
  else if (input == "John_Napier")
    cout << "the inventor of Napier's bones" << endl;
  else if (input == "Pascaline") 
    cout << "a wooden box containing a series of gears and wheels" << endl;
  else if (input == "Blaise_Pascal")
    cout << "the inventor of pascaline" << endl;
  else if (input == "Leibniz's_Wheel")
    cout << "a didgital mechanical calculater" << endl;
  else if (input == "Gottfried_Wilhelm_Leibniz")
    cout << "the inventor of Leibniz's wheel" << endl;
  else if (input == "Analytical_Engine")
    cout << "a mechanical computer that uses punch cards as input" << endl;
  else if (input == "Tabulating_Machine")
    cout << "a mechanical tabulator based on punch cards" << endl;
  else if (input == "Herman_Hollerith")
    cout << "the inventor of the tabulating machine" << endl;
  else if (input == "Differential_Analyzer")
    cout << "a mechanical analog computer used in calculations" << endl;
  else if (input == "Mark_I")
    cout << "the first programmable computer" << endl;
  else if (input == "Hard_Disk")
    cout << "a non-volatile storage device that permanently stores data" << endl;
  else if (input == "RAM")
    cout << "a volatile memory that temporarily holds data for quick access by the CPU" << endl;
   else
    cout << "ayusin mo naman wordings" << endl;
    return 0;
    }
