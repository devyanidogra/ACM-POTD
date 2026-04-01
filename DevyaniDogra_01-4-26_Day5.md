21. Merge 2 sorted lists
<img width="1907" height="808" alt="image" src="https://github.com/user-attachments/assets/389a008e-3fd5-4dcb-9d78-ee87530eb759" />

in this problem, we have to merge the sorted lists by splicing their nodes together and returning the head of the new list.

Approach: We take a dummy node (0, nullptr). We compare the nodes of the 2 lists and attach the smaller one to the dummy node. Then, we move the pointer of the list whose node is taken. After one list has been completely attached, we copy the remaining nodes of the other list onto the new list. Then return the node next to the dummy node. This takes O(m+n) time
