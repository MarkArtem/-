git init
Reinitialized existing Git repository in C:/Users/Марк/Desktop/GIT/.git/
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT>
PS C:\Users\Марк\Desktop\GIT> git commit -m ID
[master (root-commit) 98b900e] ID
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ID.txt
 create mode 100644 "\320\222\320\276\320\267\321\200\320\260\321\201\321\202.txt"
 create mode 100644 "\320\230\320\274\321\217.txt"
 create mode 100644 "\320\232\320\273\320\260\321\201\321\201.txt"
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Имя
[master 752e04f] Имя
 2 files changed, 4 insertions(+)
PS C:\Users\Марк\Desktop\GIT> git log
commit 752e04fb8812f87d5af47db261dc63fa271fabe9 (HEAD -> master)
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:32:46 2024 +0300

    Имя

commit 98b900e49392b306239338e406c8e4e2d94c45fa
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:31:35 2024 +0300

    ID
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Возраст
[master d6ea82b] Возраст
 1 file changed, 2 insertions(+)
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Класс
[master c6a73e4] Класс
 1 file changed, 2 insertions(+)
PS C:\Users\Марк\Desktop\GIT> git checkout -b Grade
Switched to a new branch 'Grade'
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Математика
[Grade bf81da4] Математика
 2 files changed, 2 insertions(+)
 create mode 100644 "\320\220\320\275\320\263\320\273\320\270\320\271\321\201\320\272\320\270\320\271.txt"
 create mode 100644 "\320\234\320\260\321\202\320\265\320\274\320\260\321\202\320\270\320\272\320\260.txt"
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Английский
[Grade 2c49e3c] Английский
 1 file changed, 2 insertions(+)
PS C:\Users\Марк\Desktop\GIT> git checkout -b Attendance
Switched to a new branch 'Attendance'
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Present
[Attendance 97d1ba5] Present
 1 file changed, 2 insertions(+)
 create mode 100644 Present.txt
PS C:\Users\Марк\Desktop\GIT> git add .
PS C:\Users\Марк\Desktop\GIT> git commit -m Absent
[Attendance 9cbfbe4] Absent
 1 file changed, 2 insertions(+)
 create mode 100644 Absent.txt
PS C:\Users\Марк\Desktop\GIT> git log
commit 9cbfbe41fde6519826375489e55a1433faaf6772 (HEAD -> Attendance)
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:53:19 2024 +0300

    Absent

commit 97d1ba556b1ab7f55415e90510ad7e8a60771d13
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:51:48 2024 +0300

    Present

commit 2c49e3caed3d2ea40f8a59705b1b9ec8fb12fb3a (Grade)
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:42:35 2024 +0300

    Английский

commit bf81da40d87b83fba01594d00807c670ff8a3e20
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:40:50 2024 +0300

    Математика

commit c6a73e4ac5f45771db73fa3feaff53ceddfacd02 (master)
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:35:05 2024 +0300

    Класс

commit d6ea82b8c5b8a2e70369ea5ad7ef41b4bac0520e
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:33:45 2024 +0300

    Возраст

commit 752e04fb8812f87d5af47db261dc63fa271fabe9
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:32:46 2024 +0300

    Имя

commit 98b900e49392b306239338e406c8e4e2d94c45fa
Author: Mark Emelyanov <novimak23@gmail.com>
Date:   Sun Dec 8 22:31:35 2024 +0300

    ID
