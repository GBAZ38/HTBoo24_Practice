# PROMPT:

We're breaking into the catacombs to find a rumoured great treasure - I hope there's no vengeful spirits down there...

---

# METHODS:

The site gave us a .zip file to download named rev_graverobber.zip

Looking at the file with the archive manager we see a folder containing a binary file named robber.

Using the `cat` command we can read the contents of the file in plain text giving us the output: 

`@@@@���yy   ���-�=�=���-�=�=�888@xxxDDS�td888@P�tdX X X $$Q�tdR�td�-�=�=00/lib64/ld-linux-x86-64.so.20GNU����GNU�+M$��I�k��%�L�GNUs � � ."puts__stack_chk_failstat__libc_start_main__cxa_finalizelibc.so.6GLIBC_2.33GLIBC_2.4GLIBC_2.2.5GLIBC_2.Ru�iTM_d\���h�P�((@�?�?�?�?�@@��H�H��/H��t��H���5�/�%�/@�%�/h������%�/h������%�/h�������1�I��^H��H���PTE1�1�H�=��;/�f.�H�=)0H�"0H9�tH�/H��t	�����H�=�/H�5�/HH�=/��.�c�����/]�f.��ff.�@���g���UH��H���dH�%(H�E�1�H�E�H�E�H�E�H�E�H�E�H�E�H�E�H�E��E�ǅ����q�����H�H��H�c.�������H��T���������H��D�/H�� ���H�E�H��H���:�����tH�H��������H�U�dH+%(t���������H�H��We took a wrong turning!We found the treasure! (I hope it's not cursed)$�������@����zRx
                                       ����&D$4h���@FJ
                                                      �?�;*3$"\y���A�C
P=
l������o���
�
 �?H��	������o����o���op���o�=6FV(@HTB{br34k1n9_d0wn_th3_sysc4ll5}GCC: (GNU) 14.2.1 20240805GCC: (GNU) 14.2.1 20240910����=X $�?:W �  @s��@�l��@@�� @� ��(@� ��@�` `&��@
       Y�@ 6"Q
              main.c_DYNAMIC__GNU_EH_FRAME_HDR_GLOBAL_OFFSET_TABLE___libc_start_main@GLIBC_2.34_ITM_deregisterTMCloneTableputs@GLIBC_2.2.5_edata_fini__stack_chk_fail@GLIBC_2.4parts__data_start__gmon_start__stat@GLIBC_2.33__dso_handle_IO_stdin_used_end__bss_startmain__TMC_END___ITM_registerTMCloneTable__cxa_finalize@GLIBC_2.2.5_init.symtab.strtab.shstrtab.interp.note.gnu.property.note.gnu.build-id.note.ABI-tag.gnu.hash.dynsym.dynstr.gnu.version.gnu.version_r.rela.dyn.rela.plt.init.text.fini.rodata.eh_frame_hdr.eh_frame.init_array.fini_array.dynamic.got.got.plt.data.bss.comment#886xx$I�� W���o�a
                                        ��i���q���opp~���o������B���  @�`` `

Unsure about what the flag is. Tried different legible strings from the output like "We took a wrong turning!We found the treasure! (I hope it's not cursed)", "@HTB{br34k1n9_d0wn_th3_sysc4ll5}", etc. 

Trying to view the file with a text editor gets us an encoding error? The file contains unknown characters and warns about editing the file and potentially corrupting it.

# SOLUTION:

Had it right the first time. The flag was `HTB{br34k1n9_d0wn_th3_sysc4ll5}`.
