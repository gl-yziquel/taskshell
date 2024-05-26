# TaskSh - TaskWarrior Shell

TaskShell or `tasksh` is a shell wrapper around taskwarrior. It
notably includes a [review][tasksh-review] command to review your
taskwarrior tasks in order to keep up to date.

[tasksh-review]: https://taskwarrior.org/docs/review/

This fork of the main tasksh repository provides the ability to
parametrise the location of your executable using the `TASKBIN`
environment variable. (I felt that need as I stumbled into a number
of issues with a name conflict between go-task's task task runner
and taskwarrior's task executable; now, I can use taskwarrior as a
locally deployed local issue tracker for my git repositories again,
without conflict with go-task's task tool...)

Development of tasksh seems to have stalled since 2020. So
[that code][tasksh-yziquel] is arguably the most recent.

[tasksh-yziquel]: https://github.com/gl-yziquel/taskshell/tree/yziquel

The [main branch displayed][tasksh-v1.2.0-yziquel] on GitHub has
backported the newest fix to the 1.2.0 version, which is the one
shipped with Debian/Ubuntu. So build this, and you'll get `TASKBIN`
as a way to parametrise the location of your taskwarrior executable.

[tasksh-v1.2.0-yziquel]: https://github.com/gl-yziquel/taskshell/tree/v1.2.0-yziquel


## Text of the old readme.

The development branch is a work in progress and may not pass all quality tests,
therefore it may harm your data. While we welcome bug reports from the
development branch, we do not guarantee proper or timely fixes.

- Make proper backups.
- Broken functionality may arise from ongoing development work.
- Be aware that using the development branch involves risks.

---

Thank you for taking a look at tasksh!!

---

Tasksh is released under the MIT license. For details check the LICENSE file.
