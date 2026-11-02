KzlBook Lite - Nguon du phong (backup)
File goc: kzlbook-lite.html (ban lay feed truc tiep tu https://3zdeptrai.blogspot.com)
Chinh: http://ln.narecords.org/kzlbook-lite.html (da test OK tren may cu, http)
Du phong 1 - GitHub Pages (https)
Du phong 2 - Cloudflare Pages (https, cung repo GitHub voi du phong 1)

CACH LAM (lam 1 lan, ca 2 host cung dung 1 repo):
1. GitHub: tao repo moi, vi du ten "kzlbook-lite", public, up file kzlbook-lite.html len nhanh main, goc repo.
2. GitHub Pages: vao repo > Settings > Pages > Build and deployment > Deploy from a branch > Branch: main, Folder: / (root) > Save.
   Doi vai phut, URL se la: https://<ten-tai-khoan>.github.io/kzlbook-lite/kzlbook-lite.html
3. Cloudflare Pages: vao Cloudflare Dashboard > Workers & Pages > Create > Pages > Connect to Git > chon dung repo "kzlbook-lite" vua tao > Framework preset: None > Build command: (de trong) > Output directory: (de trong, vi file o goc repo) > Save and Deploy.
   URL se la: https://<ten-project>.pages.dev/kzlbook-lite.html
4. Test tren may cu: mo tung URL du phong tren Safari iOS 7 (va iOS 5 neu co), xem trang chu co hien 3 truyen khong, mo 1 chuong co doc duoc khong, bam chuong truoc/sau co chay khong.
   Luu y: ca 2 host du phong deu la https, khac voi host chinh http, nen phai test rieng tren may cu, khong tu cho la chay duoc.
5. Cap nhat sau nay: khi file lite co ban moi, up de file do len ca 3 cho: narecords (chinh), GitHub repo (tu dong cap nhat ca GitHub Pages va Cloudflare Pages neu Pages noi GitHub).

App fallback (lam o buoc UI/UX sau, khong phai ban test 0.2.0):
App se thu lan luot: narecords -> GitHub Pages -> Cloudflare Pages, host nao loi thi tu chuyen sang host tiep theo.
