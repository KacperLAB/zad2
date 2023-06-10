# TCH - Zadanie 2

- Workflow został utworzony w oparciu o przykład z dokumentacji:</br>
https://docs.github.com/en/actions/publishing-packages/publishing-docker-images#publishing-images-to-github-packages

- Użyty workflow : .github/workflows/gha_test.yml

- W katalogu "ss" znajdują się zrzuty ekrany przedstawiające proces wykonywania zadania oraz efekty

- Budowanie : docker build -t test_zad2 .
- Uruchamianie : docker run -d -p 80:80 --name zad2 test_zad2
- Test CVE : docker scout cves test_zad2
- Pobranie utworzonego pakietu (obrazu) : docker pull ghcr.io/kacperlab/zad2:main


