# exercise6
itelec
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#FFFFFF"
    android:id="@+id/main"
    android:padding="20dp"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/tvTitle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/user_feedback"
        android:textColor="#3F51B5"
        android:textSize="22sp"
        android:textStyle="bold"
        android:fontFamily="sans-serif"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="40dp" />

    <ImageView
        android:id="@+id/ivIcon"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:src="@android:drawable/ic_dialog_info"
        android:contentDescription="@string/feedback_icon_desc"
        app:layout_constraintTop_toBottomOf="@id/tvTitle"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="20dp" />

    <TextView
        android:id="@+id/tvNameLabel"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/label_name"
        android:textSize="16sp"
        android:textColor="#000000"
        android:labelFor="@id/etName"
        app:layout_constraintTop_toBottomOf="@id/ivIcon"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="30dp" />

    <EditText
        android:id="@+id/etName"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="@string/hint_name"
        android:background="@android:drawable/edit_text"
        android:padding="8dp"
        android:fontFamily="sans-serif"
        app:layout_constraintTop_toBottomOf="@id/ivIcon"
        app:layout_constraintStart_toEndOf="@id/tvNameLabel"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="24dp"
        android:layout_marginStart="8dp" />

    <TextView
        android:id="@+id/tvFeedbackLabel"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/label_feedback"
        android:textSize="16sp"
        android:textColor="#000000"
        android:labelFor="@id/etFeedback"
        app:layout_constraintTop_toBottomOf="@id/etName"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="24dp" />

    <EditText
        android:id="@+id/etFeedback"
        android:layout_width="0dp"
        android:layout_height="100dp"
        android:hint="@string/hint_feedback"
        android:gravity="top"
        android:background="@android:drawable/edit_text"
        android:padding="8dp"
        android:fontFamily="sans-serif"
        app:layout_constraintTop_toBottomOf="@id/tvFeedbackLabel"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="8dp" />

    <Button
        android:id="@+id/btnSubmit"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="@string/submit_feedback"
        android:textAllCaps="false"
        android:textColor="#FFFFFF"
        android:backgroundTint="#3F51B5"
        android:padding="12dp"
        android:fontFamily="sans-serif"
        app:layout_constraintTop_toBottomOf="@id/etFeedback"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="20dp" />

</androidx.constraintlayout.widget.ConstraintLayout>
