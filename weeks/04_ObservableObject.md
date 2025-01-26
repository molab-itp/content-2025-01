# 04_ObservableObject

## [[Back](./04_swiftui.md)] [[Next](./05_data.md)]

### monitoring-model-data

- [monitoring-model-data](https://developer.apple.com/documentation/swiftui/monitoring-model-data-changes-in-your-app)

#### the basics

- ObservableObject
- @Published
- @StateObject

```
class DataModel: ObservableObject {
    @Published var name = "Some Name"

    @StateObject private var model = DataModel() // Create the state object.
```

#### sharing data between views

- environmentObject
- @EnvironmentObject
- @ObservedObject

```
struct BookReaderApp: App {
    @StateObject private var library = Library()
    LibraryView()
        .environmentObject(library)

class Library: ObservableObject {
    @Published var books: [Book] = [Book(), Book(), Book()]

class Book: ObservableObject, Identifiable {
    @Published var title = "Sample Book Title"

struct LibraryView: View {
    @EnvironmentObject var library: Library

struct LibraryView_Previews: PreviewProvider {
        LibraryView()
            .environmentObject(Library())

struct BookView: View {
    @ObservedObject var book: Book

struct BookEditView: View {
    @ObservedObject var book: Book

```
