### Installation

    composer create-project dridi-walid/punit:dev-master
    or
    git clone https://github.com/dridi-walid/punit.git && composer install
    
### Run tests

    ./bin/punit
    
Your should see the following output:

    1) Test\App\CalcTest::testSumPass() -->  PASS 
    2) Test\App\CalcTest::testSumFail() -->  FAIL, Error: Expected: 3, Result: 2

    Tests: 2  Ok: 1   Failures: 1
