guard 'shell' do
    watch(%r{.+\.adoc}) do |m|
        `asciidoctor #{m[0]}`
    end
end

guard 'livereload' do
    watch(%r{.+\.html})
end
