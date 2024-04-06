
def show_love_message():
    love_message = "I love you so much hony my love "
    message_label.config(text=love_message)

# إعداد النافذة الرئيسية
root = tk.Tk()
root.title("My Love")

# إضافة عنوان
title_label = tk.Label(root, text="Program Wissam", font=("Arial", 20))
title_label.pack()

# إضافة زر لإظهار رسالة الحب
show_message_button = tk.Button(root, text="Mouhiddine", command=show_love_message)
show_message_button.pack()

# إضافة مكان لعرض رسالة الحب
message_label = tk.Label(root, text="", font=("Arial", 10))
message_label.pack()

# بدء البرنامج
root.mainloop()
